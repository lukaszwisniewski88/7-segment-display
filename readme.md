Seven Segment Display
====

A minimal react component for seven segment display.

![](https://i.gyazo.com/3b6a38074818065bc79d1e0ccf74a509.gif)


### Installation

**npm**

```bash
npm install 7-segment-display --save
```

**yarn**

```bash
yarn add 7-segment-display
```

**Example**

```
import React from 'react';
import SevenSegmentDisplay from "7-segment-display"

function App() {

  return (
    <div className="App">
        <SevenSegmentDisplay number={3}></SevenSegmentDisplay>
        <SevenSegmentDisplay ledColorOn={"green"} number={7}></SevenSegmentDisplay>
        <SevenSegmentDisplay ledBorder={"transparent"} ledColorOn={"black"} ledColorOff={"black"} number={3}></SevenSegmentDisplay>
    </div>
  );
}

export default App;
```
![](https://imgur.com/RaxxVdp)

Thanks
