block-generator
===============

Register bundle in AppKernel.php

    public function registerBundles()
    {
    
            new Jse\BlockGeneratorBundle\JseBlockGeneratorBundle(),
            
    }

command:

php app/console create:block "block name" --bundle=AcmeDemoBundle
