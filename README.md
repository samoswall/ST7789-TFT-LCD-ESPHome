# ST7789-TFT-LCD-ESPHome
Display Component ST7789 TFT LCD 240x240 for ESPHome (not used reset_pin)

# Настройка ESPHome
Поместить папку st7789v с ее содержимым в папку my_components Вашей ESPHome\
Пример использования в коде программы
```yaml
display:
  - platform: st7789v
    reset_pin: GPIO23                    
    dc_pin: GPIO16
    id: my_display
    dimensions: 240x240
    update_interval: 0.5s
```
С этим модифицированным компонентом корректно работает дисплей ST7789 240х240 без использования reset_pin
