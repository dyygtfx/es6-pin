使用说明：

`require('bower_components/pin')`或`require('Pin')`

```
new Pin('.record-top-banner','.record-head',30, {
  onPin: function() {

  },
  onUnpin: function() {

  }
});
```
- `.record-top-banner` 表示你需要固定在顶部的元素（必填）
- `.record-head` 表示当滚动超过这个元素的时候开始固定（可选,不填则是0）
- `30` 表示在 `.record-head` 的基础上再加 30象素高，可自定义。（可选，不填则是0）
- `onPin` 表示当固定的时候执行的回调
- `onUnpin` 表示当移除固定的时候执行的回调
