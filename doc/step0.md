# Step 0 �͂��߂悤

## Q1.�����̕\��
### �u���E�U�ŕ\�����Ă݂悤
```
./src/step0/q-0-1/html/ms.html
```

### ���
HTML����*message*�ɑ΂��āAJavaScript�ŕ������ݒ肵�Ă��܂��B
HTML�ɒ��ڕ������L�q������A���_��ɕύX���邱�Ƃ��ł��܂��B
�����Ɍ��炸�\�₻�̑��̑����ɂ��Ă��A��{�I��JavaScript����w�肷�邱�ƂɂȂ�܂��B
�X�^�C���ɂ��Ă�`ms.css`���Q�Ƃ��Ă��������B

- ms.html

```html
	<div id="main" class="container">
	<div id="message"></div>
```

- ms.js

```js
(function () {
	$('#message').text('welcome to javascript-ms')
	})();
```

### ����Ă݂悤
�E�\�����镶���̓��e��ς��Ă݂܂��傤�B
�E�����̐F��ς��Ă݂���A�E�񂹂⍶�񂹂ɂ��Ă݂܂��傤�B

### �q���g
���{��̕����͂��܂��\�������ł��傤���B
��{�I�ɕ����R�[�h��UTF-8�𗘗p���܂��̂ŁA�t�@�C����ҏW����Ƃ��̕����R�[�h���m�F���Ă݂܂��傤�B


## Q2.�\�̕\��
### �u���E�U�ŕ\�����Ă݂悤
```
./src/step0/q-0-2/html/ms.html
```

### ���
�\�ɂ��Ă����l��JavaScript�ŋL�q���s���܂��B
�ʏ��`<table>`�^�O�𗘗p����HTML���L�q���܂����A�����s�ɂ܂����邽�߂����ł͔z��𗘗p���Ă��܂��B
`join`�֐��̈�����separator�ɂȂ�܂����A�����ł͋󕶎�`''`���w�肳��Ă��邱�Ƃɒ��ӂ��Ă��������B
�z��Ɋi�[����Ă��镶���񂪂��̂܂܌�������A`<table>`�^�O���\������邱�ƂɂȂ�܂��B

### ����Ă݂悤
�E�������ꂽ`<table>`�^�O�̓��e��\�����Ă݂܂��傤�B
�E�\������\��4�~4�ɂ��Ă݂܂��傤�B

### �q���g
`table`�v�f�̍\�z�ɂ͕�����𗘗p���Ă��܂����A���̕��@�͂ǂ��炩�Ƃ����Ό��n�I�Ȃ����ł���A�m���ł͂���܂����_����邪�䂦�ɕێ琫��ǐ������Ȃ��Ă��܂��B
`createElement`�Ȃǂ𗘗p���邱�Ƃł��*�v�f���\�z���Ă���*�Ƃ������������m�ɂȂ�A���A�@�\�I�ɂ��Ǝ��̎������Ƃ̕������}��܂��B
�]�T������΂���𗘗p���Ă݂܂��傤�B