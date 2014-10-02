QrCode-Generator
================

Simple displaying of QR codes.
See https://google-developers.appspot.com/chart/infographics/docs/qr_codes for more infos.

Includes functions to create QR codes for text.


Usage:
* Copy the "QrCode.php" to your folder.
* In the view for example do 
"
<?php $qr = new QrCode();
echo $qr->text('Hello'); ?>"
