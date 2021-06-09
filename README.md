# Blink Example

Starts a FreeRTOS task to blink an LED

See the README.md file in the upper level 'examples' directory for more information about examples.

```mermaid
graph TD
A(start)
```

```sequence {theme="hand"}
MCU->Sensor: Start

```

```wavedrom
{
    signal: [
        {
            name: 'SCL',
            wave: '1.0101010101010'
        },
        {
            name: 'SDA',
            wave: '103.4.5.6.7.8.0',
            data: ['D6','D7','R/W','ACK','D0','D1']
        }
    ] 
}
```