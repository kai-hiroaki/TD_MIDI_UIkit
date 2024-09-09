# TD_MIDI_UIkit

TouchDesigner の MIDI アサイン可能な UI パーツ集です。

Palette の BasickWidget をベースに作成しているため、普段とほぼ同じ使用感でお使いいただけます。

## tox

### manager_MIDI

- MIDI In CHOP や、MIDI アサインのためのパネルのオンオフを管理しています。
- /project1 の子要素として配置してください。

### masterButton_MIDI

- MIDI アサインが可能なボタンコンポーネントです。
- 自由な場所に配置してください。
- 通常の masterButton のように、Type を Momentary や Toggle 等に切り替えて使用することが出来ます。
- MIDI OUT が設定できます。
  - Off Value, On Value を MIDI コントローラーに応じた数値に設定してください。

### masterKnob_MIDI

- MIDI アサインが可能なノブコンポーネントです。
- 自由な場所に配置してください。

### sliderVert_MIDI

- MIDI アサインが可能なスライダーコンポーネントです。
- 自由な場所に配置してください。

## アサイン方法

manager_MIDI の MIDI SETTING ボタンを押すと MIDI アサインモードになります。
アサインしたいコンポーネントを選択し、MIDI コントローラーを動かすとアサインされます。
