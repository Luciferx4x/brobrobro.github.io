<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>X</title>
<style>

    .background-dark {

background-color: #000;
    }
    .center {
display: flex;
justify-content: center;
}
.margin-top {
margin-top: 100px;

}
</style>
<script>
var speechElement = new webkitspeechRecognition();
speechElement.lan = 'de-DE';
speechElement.interimResults = true;
speechElement.continuous = true;
var final_transcript = '';
speechElement.start(start);


speechElement.onstart = function(start) {
console.log('start');

}

</script>
  
  <script type="text/javascript">
    var adfly_id = 26383945;
    var adfly_advert = 'int';
    var popunder = true;
    var domains = ['depositfiles.com', 'rapidshare.com', 'vip-file.com', 'smsfiles.ru', '4files.net', 'turbobit.ru', 'uploading.com', 'letitbit.net', 'depositfiles.ru', 'sms4file.com', 'ifolder.ru', 'hotfile.com', 'anyfiles.net', 'sharingmatrix.com', 'megashare.com', 'megaupload.com', 'rapidshare.de', 'rapidshare.ru', 'uploadbox.com', 'filefactory.com', 'filefactory.ru', 'filepost.ru', 'onefile.net', 'freefolder.net', 'getthebit.com', 'turbobit.net'];
    var adfly_domain = 'j.gs';
  </script>
<script src="https://cdn.adf.ly/js/link-converter.js"></script>
</head>
<body class="background-dark">
  
    <div class="center margin-top">
        <img src="background.gif"
        width="777" height="437"
        
        >
   
        </div>
       

  
        <div class="center margin-top">
            <img src="button.png">
            
                    </div>
                    <div class="center margin-top">
                        <button class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored">
                            Start
                          </button>
                          <button id="voiceSearchButton" title="Sprachsuche verwenden"></button>
                        </div>
<div id="output">
<span id="final" class="final"></span>
<span id="interim" class="interim"></span>
</div>
</body>
</html>
