# Electronic_Khipu_

The **Electronic_Khipu_** is a NIME designed to create live experimental sound through knot-making with conductive rubber cords. It is inspired by the *Khipu*, an ancient information storage and transmission device used by the Incas and earlier Andean societies. Its name comes from the Kichwa word “khipu,” meaning “knot.”

>A khipu consists of a central cord from which secondary strings are detached with knots of different shapes, colors, and sizes that constituted a set of signs that could be used to make numerical records or to account for important facts or events. The khipu has been known for its accounting and statistical utilities, but nowadays it has been discovered that the Khipus also contained several layers of memory that include not only arithmetic data butalso economic, social, biological, historical, astronomical, linguistic and literary records (Cadavid, NIME 2020).

The concept behind the **Electronic_Khipu_** is to revive this ancient device, offering a different interpretation than the Western view, which sees it solely as a numerical system for observation and study, devoid of deeper meaning or "soul." Instead, the **Electronic_Khipu_** reuses the Khipu’s code system to create new messages and sonic narratives.

https://www.patriciacadavid.net/search/label/electronic-khipu 

![Electronic_Khipu_ Instrument](documentation/images/Electric_Khipu_5strings.jpg)

## Technical notes
The **Electronic_Khipu_** consists of a root cord and five secondary strings arranged in a wooden box with various potentiometers and buttons to control the signal. The secondary cords are made from conductive rubber sensors, which function as variable resistors to measure tension that increases with each knot added. The entire setup is managed by a Teensy board in order to control the sensors and the potentiometers and send MIDI messages to a computer. The artist interacts with these cords by touching and knotting them during a performance. The sound textures depend on the performer's skin conductivity and the intensity of touch while making knots. A cable connects the performer (through a ring or a bracelet) to the system ground, completing a circuit upon touch and altering the signals produced by each cord. Each knot anchors the cord to a grounded metal piece, with tension tailored to each knot’s strength. 
During the performance, the instrument is usually combined with a camera to visualise the performer’s gesture in real-time.

## Instruction
[Go to the instructions for building the Electronic_Khipu_.](documentation/instructions/README.md)

## Cite Repository
```text
@software{Cadavid_Electronic_Khipu,
    author = {Cadavid, Patricia},
    license = {GPL-3.0},
    title = {{Electronic\_Khipu\_}},
    url = {https://github.com/lpatriciacadavid/Electronic_Khipu_}
}
```

```text
Cadavid, P. Electronic_Khipu_ [Computer software]. https://github.com/lpatriciacadavid/Electronic_Khipu_
```

See [Documentation](documentation) for related articles