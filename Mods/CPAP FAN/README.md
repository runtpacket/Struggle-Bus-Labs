Remote Colling using a Resmed CPAP Fan 
```
[fan]
pin: PB6
hardware_pwm: True
shutdown_speed: 0
kick_start_time: .25
max_power: 1 # adjust below 1 if you would like the max speed to be slower
off_below: 0.06 # minimum speed where the fan starts spinning - on octopus pro this is correct - will be lower maybe 0 on mellow Super 8 because of different GPIO pullup and protection resistors
cycle_time: .00004 # = 2khz - CPAP fan driver recommended range is 2-50khz
#tachometer_pin:^PG13
#tachometer_ppr: 2
```

![RESMED CPAP Fan](RESMED_Fan.jpg)

![RioRand 300W 5-50V PWM DC Brushless Electric Motor Speed Controller with Hall-Less](FSC.jpg)

[RioRand 300W 5-50V PWM DC Brushless Electric Motor Speed Controller with Hall-Less](https://www.amazon.com/dp/B087M3GVYX?ref=ppx_yo2ov_dt_b_product_details&th=1)

[Fan speed controoler on amazon](https://www.amazon.com/dp/B087M3GVYX?ref=ppx_yo2ov_dt_b_product_details&th=1)

