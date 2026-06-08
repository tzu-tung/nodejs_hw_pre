#Todolist RESTful API kata 
1.server.js
**注意** 需要先宣告 const todos = [];

2.error.js
**注意** import errHandle from './errorHandle.js';

3.errorHandle.js
**注意** export default errorHandle; 

4.dele.js
**注意** 需要先寫刪除單筆的狀況，再寫刪除全部的狀況
🔴 不然執行下來會都是刪除全部

**需要調整 "type": "module"**
import http from 'http';
import { v4 as uuidv4 } from "uuid";
import errHandle from './errorHandle.js';

**注意 res.end(); 的位置**
