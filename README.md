# Stash
Stash: Flexible Energy Storage for Intermittent Sensors

Batteryless sensors promise a sustainable future for sensing, but they face significant challenges when storing and using
environmental energy. Incoming energy can fluctuate unpredictably between periods of scarcity and abundance, and device
performance depends on both incoming energy and how much a device can store. Existing batteryless devices have used fixed
or run-time selectable front-end capacitor banks to meet the energy needs of different tasks. Neither approach adapts well to
rapidly changing energy harvesting conditions, nor does it allow devices to store excess energy during times of abundance
without sacrificing performance.

This paper presents Stash, a hardware back-end energy storage technique that allows batteryless devices to charge quickly
and store excess energy when it is abundant, extending their operating time and carrying out additional tasks without
compromising the main ones. Stash performs like a small capacitor device when small capacitors excel and like a large
capacitor device when large capacitors excel, with no additional software complexity and negligible power overhead. We
evaluate Stash using two applications—temperature sensing and wearable activity monitoring—under both synthetic solar
energy and recorded solar and thermal traces from various human activities. Our results show that Stash increased sensor
coverage by up to 15% under variable energy-harvesting conditions when compared to competitor configurations that used
fixed small, large, and reconfigurable front-end energy storage.
