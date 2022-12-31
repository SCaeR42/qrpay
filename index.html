<!doctype html>
<html lang="ru">
<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <link rel="icon" type="image/png" href="/qr/qrpay/favicon.png"/>

    <title>Генератор QR ссылки на оплату через СМС для Сбербанка</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" type="text/css"/>

    <link href="css/style.css" rel="stylesheet" type="text/css"/>


</head>
<body>

<header role="main">
    <div class="container">

    </div>
</header>

<main role="main" class="flex-shrink-0">
    <div class="container">

        <div class="widget widget-qr-generator js-widget-card">
            <div class="widget-header">
                <h3>Генератор QR ссылки на оплату через СМС для Сбербанка</h3>
            </div>
            <div class="widget-body">

                <form class="js-qr-form" action="" onsubmit="return false;">
                    <div class="form-group">
                        <label for="phone">Номер телефона получателя, начиная с девятки *</label>
                        <input type="text"
                               name="phone"
                               id="phone"
                               required
                               class="form-control js-qr-phone"
                               placeholder="9101231111"
                        >
                    </div>

                    <div class="form-group">
                        <label for="price">Сумма перевода</label>
                        <input type="text"
                               name="price"
                               id="price"
                               value="1"
                               class="form-control js-qr-price"
                               placeholder="100"
                        >
                    </div>

                    <div class="form-group form-group--btn">
                        <button class="input-group-text
                        btn btn-primary
                        js-qr-genCode"
                                type="button">Генерировать!
                        </button>
                    </div>

                </form>

                <div class="desc">
                    <p>Будет сгенерирован QR код при сканировании которого на телефоне откроется СМС для отправки в Сбер на указаную сумму перевода.</p>
                    <p>Так же будет отображена кнопка при клике которой на телефоне сгенерируется смс для отправки с Сбер.</p>
                </div>

                <div class="js-btn-result btn-result d-none">
                    <a href="javascript:;" class="btn btn-primary">Создать СМС</a>
                </div>
                <div class="js-qr-result qr-result"></div>

            </div>
        </div>

    </div>
</main>

<footer role="footer">
    <div class="container">

    </div>
</footer>

<!-- Optional JavaScript -->
<script src="//cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js" type="text/javascript"></script>
<script src='//cdn.jsdelivr.net/npm/jquery@3.2.1/dist/jquery.min.js'></script>
<script src='//cdn.jsdelivr.net/npm/qrcodejs@1.0.0/qrcode.js'></script>

<script type="text/javascript">
    jQuery(document).ready(function ($) {
        let $phoneWrap = jQuery('.js-qr-phone');
        let $priceWrap = jQuery('.js-qr-price');
        let $resWrap = jQuery('.js-qr-result');

        let qrcode = new QRCode($resWrap[0], {
            width: 300,
            height: 300
        });

        function makeCode() {
            let phone = $phoneWrap.val();
            let price = $priceWrap.val() || 1;

            if (!phone) {
                alert("Укажите телефон");
                $phoneWrap.focus();
                return;
            }

            let qrData = 'sms:900?&body=Перевод ' + phone + ' ' + price;

            qrcode.makeCode(qrData);
            jQuery('.js-btn-result').attr('href', qrData).removeClass('d-none');
        }

        jQuery(document).on('click', '.js-qr-genCode', function (e) {
            jQuery(document).trigger('genQrCode');
        });

        jQuery(document).on('genQrCode', function (event) {
            makeCode();
        });
    });
</script>

</body>
</html>