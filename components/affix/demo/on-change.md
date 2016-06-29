---
order: 3
title:
  zh-CN: 固定状态改变的回调
  en-US: Callback
---

## zh-CN

可以获得是否固定的状态。

## en-US

Callback with affixed state.

````jsx
import { Affix, Button } from 'antd';

function onChange(affixed) {
  console.log(affixed); // true or false
}

ReactDOM.render(
  <Affix offsetTop={120} onChange={onChange}>
    <Button>120px to affix top</Button>
  </Affix>
, mountNode);
````
