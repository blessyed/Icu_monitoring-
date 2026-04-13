# Smart ICU Patient Bed Monitoring System

## Objective

To simulate an ICU patient monitoring system using STM32, where environmental conditions and patient safety alerts are monitored in real time.

## Hardware Used

* STM32 Nucleo Board
* Potentiometer
* Ultrasonic Sensor
* Servo Motor
* Fan
* Buzzer
* LED
* OLED Display
* External Button

## Components and Purpose

* **Potentiometer** → simulates temperature variation
* **Ultrasonic Sensor** → detects patient movement / unsafe distance
* **Servo Motor** → simulates medicine valve control
* **Fan** → automatic cooling during high temperature
* **Buzzer** → emergency alert
* **LED** → warning indication
* **OLED Display** → system status display
* **External Button** → nurse acknowledgment / manual control

## Working Principle

* Potentiometer is rotated to simulate temperature increase.
* When temperature crosses threshold, fan turns ON automatically.
* Ultrasonic sensor detects nearby movement and triggers buzzer alert.
* Servo motor simulates medicine valve opening during emergency condition.
* LED indicates warning condition.
* OLED displays system status continuously.

## Example Display Output

TEMP: 32C
ALERT: ON
FAN: ON

## Real-Life Application

This simulates how ICU monitoring systems supervise patient condition, environmental temperature, and emergency response using embedded control logic.

## Development Platform

* STM32CubeIDE
* STM32 HAL Library
