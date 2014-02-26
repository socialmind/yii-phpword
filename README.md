yii-phpword
===========

A wrapper / clone of yii-phpexcel (@marcovtwout) for the PHPWord library.

###Install:###

1. Unzip the contents of this directory to protected/extensions/phpword
2. Download the latest version of PHPWord: https://phpword.codeplex.com/
3. Unzip the contents of the folder Classes to a new folder protected/extensions/phpword/vendor

###Usage:###

    Yii::import('ext.phpword.XPHPWord');      
    $phpWord = XPHPWord::createPHPWord();

Or if you don't want a PHPWord object:

    Yii::import('ext.phpword.XPHPWord');      
    XPHPWord::init();
