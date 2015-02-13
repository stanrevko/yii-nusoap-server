# yii-nusoap-server
yii-nusoap-server



## Installation
<?php

require_once Yii::app()->basePath . '/extensions/nusoap/nusoap.php';

class SiteController extends Controller
...
public function actions() {
        return array(
            'soap'=>"SoapAction",
            
        );
    }
