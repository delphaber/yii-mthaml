Yii MtHaml
========
Yii's extension for Haml template system, using [MtHaml](https://github.com/arnaud-lb/MtHaml) library.

## Instructions
* Code must be in this folder 'protected/extensions/yii-mthaml/'
* Since I'm using git submodules, you need to init them:

    ```bash
    cd protected/extensions/yii-mthaml
    git submodule init
    git submodule update
    ```
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
