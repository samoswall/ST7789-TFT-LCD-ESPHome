# ST7789-TFT-LCD-ESPHome
Display Component ST7789 TFT LCD 240x240 for ESPHome (without CS pin)

# Настройка ESPHome
* Поместить папку st7789v с ее содержимым в папку my_components Вашей ESPHome\
Пример использования в коде программы\
* Place the st7789v folder with its contents in the my_components folder of your ESP Home\
Example of use in the program code
```yaml
display:
  - platform: st7789v
    reset_pin: GPIO23                    
    dc_pin: GPIO16
    id: my_display
    dimensions: 240x240
    update_interval: 0.5s
```
* С этим модифицированным компонентом корректно работает дисплей ST7789 240х240 без использования CS_pin\
Работа проверялась на дисплее 240х240 купленном на AliExpress\
* The ST7789 240x240 display works correctly with this modified component without using CS_pin\
The work was checked on a 240x240 display purchased on AliExpress\
![all](https://github.com/samoswall/ST7789-TFT-LCD-ESPHome/blob/main/st7789%20without%20CS%20pin.jpg)
