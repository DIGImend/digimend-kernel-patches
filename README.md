DIGimend kernel patches
=======================

The digimend-kernel-patches package contains patches for a few older Linux
kernel versions, both improving general support for graphics tablets and
adding drivers for specific tablets.

Kernel and tablet support is as follows.

    VID:PID     Original model                      stable  ubuntu      stable
                                                    3.2.28  3.2.0-30.48 3.0.42

    0458:5010   KYE EasyPen i405X                   +       +           +
    0458:5011   KYE MousePen i608X                  +       +           +
    0458:5013   KYE EasyPen M610X                   +       +           +
    172f:0032   Waltop Slim Tablet 5.8"             =       =           =
    172f:0034   Waltop Slim Tablet 12.1"            =       =           =
    172f:0037   Waltop Q Pad                        +       +           +
    172F:0038   Waltop PID 0038                     +       +           +
    172f:0500   Waltop Media Tablet 14.1"           =       =           =
    172f:0501   Waltop Media Tablet 10.6"           =       =           =
    172F:0502   Waltop Sirius Battery Free Tablet   +       +           +
    5543:0003   UC-Logic Tablet WP4030U             =       =           =
    5543:0004   UC-Logic Tablet WP5540U             =       =           =
    5543:0005   UC-Logic Tablet WP8060U             =       =           =
    5543:0042   UC-Logic Tablet PF1209              =       =           =
    5543:0064   UC-Logic Tablet WP1062              =       =           +
    5543:0522   UC-Logic Wireless Tablet TWHL850    +       +           +
    5543:0781   UC-Logic Tablet TWHA60              +       +           +

    +   tablet support is added by patches
    =   tablet is supported by this kernel as is, without patches
    -   tablet is not supported by this kernel/patches

See [digimend-kernel-drivers][1] for out-of-tree drivers for newer tablets and
kernel versions.

[1]: https://github.com/DIGImend/digimend-kernel-drivers
