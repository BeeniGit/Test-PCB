# Test-PCB

```wave
<WaveDormHeader>
  {signal: [
    {name: 'clk', wave: 'p.....|...'},
    {name: 'dat', wave: 'x.345x|=.x', data: ['head', 'body', 'tail', 'data']},
    {name: 'req', wave: '0.1..0|1.0'},
    {},
    {name: 'ack', wave: '1.....|01.'}
  ]}
</WaveDormHeader>
```

```mermaid
graph LR
  A --> B;
  B --> A;
```

![Timing diagram](https://svg.wavedrom.com/github/BeeniGit/Test-PCB/main/waveform.json5)

![Timing diagram](https://svg.wavedrom.com/github/BeeniGit/Test-PCB/main/signal-step4.json5)

![Timing diagram](https://svg.wavedrom.com/github/BeeniGit/Test-PCB/main/test_svg/signal-step4.json5)
![signal step4](https://svg.wavedrom.com/github/wavedrom/wavedrom/trunk/test/signal-step4.json5)

![reg vl](https://svg.wavedrom.com/github/wavedrom/wavedrom/trunk/test/reg-vl.json5)

<img src="https://svg.wavedrom.com/{signal:[{name:'clk',wave:'p......'},{name:'bus',wave:'x.34.5x',data:'head body tail'},{name:'wire',wave:'0.1..0.'}]}"/>
