    git clone https://github.com/Iceows/huawei-creator.git huawei-creator-11
.

    cd huawei-creator
-
Generate ARM64 AB (Huawei device) from ARM64 AB and include patchs and optimisations (target image name is s-ab.img):

    sudo ./run-huawei-ab.sh systemAB.img "LeaOS"

Generate ARM64 A-only (Huawei device) from ARM64 AB . (target image name is s-aonly.img),  (deprecated since Android 12): 

    sudo ./run-huawei-aonly.sh systemAB.img "LeaOS"
:     

    sudo bash run-huawei-aonly.sh systemAB.img "LeaOS"
Generate ARM64 A-only (Huawei device) from ARM64 A-only . (target image name is s-aonly.img),  (deprecated since Android 12): 

    ssudo bash udo ./run-huawei-a-to-a.sh system.img "LeaOS"
