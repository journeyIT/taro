---
title: Taro.offAccelerometerChange(callback)
sidebar_label: offAccelerometerChange
id: version-2.1.1-offAccelerometerChange
original_id: offAccelerometerChange
---

取消监听加速度数据事件，参数为空，则取消所有的事件监听。

> [参考文档](https://developers.weixin.qq.com/miniprogram/dev/api/device/accelerometer/wx.offAccelerometerChange.html)

## 类型

```tsx
(callback: (...args: any[]) => any) => void
```

## 参数

<table>
  <thead>
    <tr>
      <th>参数</th>
      <th>类型</th>
      <th>说明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>callback</td>
      <td><code>(...args: any[]) =&gt; any</code></td>
      <td>加速度数据事件的回调函数</td>
    </tr>
  </tbody>
</table>

## API 支持度

| API | 微信小程序 | H5 | React Native |
| :---: | :---: | :---: | :---: |
| Taro.offAccelerometerChange | ✔️ |  |  |
