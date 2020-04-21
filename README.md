# tf-cypress
TF on Cypress

```
gmake -f tensorflow/lite/micro/tools/make/Makefile TARGET=mbed  generate_hello_world_mbed_project
cd  tensorflow/lite/micro/tools/make/gen/mbed_cortex-m4/prj/hello_world/mbed


mbed compile -c  -f -m CY8CPROTO_062_4343W  -t GCC_ARM
```
