<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>ゆるきせかえ</title>

<style>
body {
  background: #f7f3ff;
  font-family: sans-serif;
  text-align: center;
}

.きせかえ {
  position: relative;
  width: 200px;
  margin: 40px auto;
}

.きせかえ img {
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
}

/* 初期は服を隠す */
#ふく1, #ふく2 {
  display: none;
}

/* チェックされたら表示 */
#btn1:checked ~ .きせかえ #ふく1 {
  display: block;
}

#btn2:checked ~ .きせかえ #ふく2 {
  display: block;
}

.ボタン {
  margin-top: 260px;
}
label {
  background: #e3d9ff;
  padding: 8px 12px;
  border-radius: 12px;
  margin: 4px;
  cursor: pointer;
  display: inline-block;
}
</style>
</head>

<body>

<h2>ゆるきせか
