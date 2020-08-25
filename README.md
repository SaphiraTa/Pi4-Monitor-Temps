#!/bin/bash
#Measure CPU Temps and CPU Freq (& GPU Freq - Not Working) for RasPi4 running Ubuntu-ARM-Server 20.04.1 - RUNS SIZE 33x4 PERFECTLY

watch -n 1 "cat /sys/class/thermal/thermal_zone0/temp; cat /sys/devices/system/cpu/cpu0/cpufreq/scaling_cur_freq"
