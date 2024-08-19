# mediatek_debian
mediatek debian firmware (mt7921au)



    mkdir -p /opt/wifi_install && \
    cd /opt/wifi_install && \
    git clone https://github.com/deaffella/mediatek_debian.git && \
    cd mediatek_debian/mediatek && \
    xz -d *.xz 
    xz -d */*.xz
    cd ..
    cp -r /opt/wifi_install/mediatek_debian/mediatek /usr/lib/firmware/
