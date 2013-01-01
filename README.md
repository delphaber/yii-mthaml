Yii MtHaml
========
Yii's extension for Haml template system, using [MtHaml](https://github.com/arnaud-lb/MtHaml) library.

## Instructions
* Place this code into 'protected/extensions/yii-mthaml/' folder
* Add this to your 'config/main.php' file:
    
    ```php
    'components'=>array(
        ...
        'viewRenderer'=>array(
            'class' => 'ext.yii-mthaml.CMtHamlViewRenderer',
        ),
        ...
    ```

* Haml templates must have '.haml' extension
