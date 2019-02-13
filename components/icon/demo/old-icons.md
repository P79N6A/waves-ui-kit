---
order: 10
debug: true
title:
  zh-CN: 老版图标
  en-US: Test old icons
---

## zh-CN

测试 3.9.0 之前的老图标。

## en-US

Test old icons before `3.9.0`.

````jsx
import { Icon } from 'antd';

const icons = [
  'step-forward',
  'icon-send'
];

ReactDOM.render(
  <div>
    {icons.map(icon => <Icon key={icon} type={icon} />)}
  </div>,
  mountNode
);
````
