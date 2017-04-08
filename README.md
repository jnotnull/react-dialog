[![Github All Releases](https://img.shields.io/github/downloads/atom/atom/total.svg)]()
[![npm](https://img.shields.io/npm/v/npm.svg)]()

## react-dialog

## Install

	npm install react-dialog

## Usage

import:

	import Dialog from 'react-dialog';
	import 'react-dialog/dist/dialog.css';

in JSX:

	<Dialog ref='dialog'/>

in click:

	this.refs.dialog.show({
      config: {
        title: '提示信息',
        tip: '确定取消？'
      },
      okfunc: function(){
          location.href = "#/ctrldesk"
        }.bind(this)
    });

## Compile

	babel ./src/dialog.js --out-file ./dist/dialog.js