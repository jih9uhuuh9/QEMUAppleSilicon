system_ss.add(files('soundhw.c'))
system_ss.add(when: 'CONFIG_AC97', if_true: files('ac97.c'))
system_ss.add(when: 'CONFIG_ADLIB', if_true: files('fmopl.c', 'adlib.c'))
system_ss.add(when: 'CONFIG_ASC', if_true: files('asc.c'))
system_ss.add(when: 'CONFIG_CS4231', if_true: files('cs4231.c'))
system_ss.add(when: 'CONFIG_CS4231A', if_true: files('cs4231a.c'))
system_ss.add(when: 'CONFIG_ES1370', if_true: files('es1370.c'))
system_ss.add(when: 'CONFIG_GUS', if_true: files('gus.c', 'gusemu_hal.c', 'gusemu_mixer.c'))
system_ss.add(when: 'CONFIG_HDA', if_true: files('intel-hda.c', 'hda-codec.c'))
system_ss.add(when: 'CONFIG_MARVELL_88W8618', if_true: files('marvell_88w8618.c'))
system_ss.add(when: 'CONFIG_PCSPK', if_true: files('pcspk.c'))
system_ss.add(when: 'CONFIG_PL041', if_true: files('pl041.c', 'lm4549.c'))
system_ss.add(when: 'CONFIG_SB16', if_true: files('sb16.c'))
system_ss.add(when: 'CONFIG_VT82C686', if_true: files('via-ac97.c'))
system_ss.add(when: 'CONFIG_WM8750', if_true: files('wm8750.c'))
system_ss.add(when: ['CONFIG_VIRTIO_SND', 'CONFIG_VIRTIO'], if_true: files('virtio-snd.c'))
system_ss.add(when: ['CONFIG_VIRTIO_SND', 'CONFIG_VIRTIO', 'CONFIG_VIRTIO_PCI'], if_true: files('virtio-snd-pci.c'))

subdir('apple-silicon')
