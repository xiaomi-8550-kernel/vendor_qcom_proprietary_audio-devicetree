ifeq ($(CONFIG_ARCH_KALAMA), y)
dtbo-y += kalama-audio.dtbo \
                 kalama-audio-cdp.dtbo \
                 kalama-audio-cdp-nfc.dtbo \
                 kalama-audio-wsa883x-cdp.dtbo \
                 kalama-audio-cdp-apq.dtbo \
                 kalama-audio-mtp.dtbo \
                 kalama-audio-mtp-nfc.dtbo \
                 kalama-audio-mtp-apq.dtbo \
                 kalama-audio-qrd.dtbo \
                 kalama-audio-atp.dtbo \
                 kalama-audio-rcm.dtbo \
                 kalama-audio-rumi.dtbo \
                 kalama-audio-hdk.dtbo \
                 kalama-sg-audio-hhg.dtbo \
                 nuwa-audio-mtp.dtbo \
                 ishtar-audio-mtp.dtbo \
                 babylon-audio-mtp.dtbo \
                 fuxi-audio-mtp.dtbo \
                 wangshu-audio-mtp.dtbo \
                 socrates-audio-mtp.dtbo \
                 vermeer-audio-mtp.dtbo \
                 sheng-audio-mtp.dtbo
endif

ifeq ($(CONFIG_ARCH_SA8155), y)
dtbo-y +=  sa8155-audio.dtbo
endif

ifeq ($(CONFIG_ARCH_KHAJE), y)
dtbo-y += khaje-audio.dtbo \
		khaje-audio-idp.dtbo \
		khaje-audio-qrd.dtbo \
		khaje-audio-qrd-hvdcp3p5.dtbo \
		khaje-audio-idp-nopmi.dtbo \
                khajeg-audio-idp.dtbo \
                khajeg-audio-idp-90hz.dtbo \
		khaje-nowcd.dtbo
endif

ifeq ($(CONFIG_ARCH_CROW), y)
dtbo-y += crow-audio.dtbo \
                 crow-audio-idp.dtbo \
                 crow-audio-idp-wcd9395-aatc.dtbo \
                 crow-audio-idp-wcd9395-dmic.dtbo \
                 crow-audio-idp-wcd9395-wcd-dmic.dtbo \
                 crow-audio-qrd.dtbo \
                 crow-audio-atp.dtbo
endif

 always-y    := $(dtb-y) $(dtbo-y)
 subdir-y    := $(dts-dirs)
 clean-files    := *.dtb *.dtbo
