# golang-go_no-mmx
Patch/es for Go to build binaries for Intel Quark CPU (Galileo/Siemens IOT)

This is based on the siemens/meta-iot2000 patches by jan-kiszka.
Working on the Master Branch at 8a317ebc0f50339628c003bf06107cd865406dd4
ALL TESTS PASSED for a manual build of "Go" itself.



https://www.loraserver.io/lora-gateway-bridge/ appears to work ok with GOARCH="386" GO386="quark" make build


https://github.com/influxdata/influxdb  needs much more work to build with this patch.







