ASPEED AST2600 Evaluation Board
================

This is the ASPEED AST2600 evaluation board layer.
The AST2600 is an ARM, service management SOC made by ASPEED. More information
about the AST2600 can be found
[here](http://aspeedtech.com/server_ast2600/).

For AST2600 EVB image, please use the following command to build.
```
TEMPLATECONF=meta-evb/meta-evb-aspeed/meta-evb-ast2600/conf . openbmc-env
bitbake obmc-phosphor-image
```
