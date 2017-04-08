# kangxi-strokecount

A chinese character stroke count lookup table according to Kangxi Zidian (康熙字典) radical rules.

Includes all chinese characters in Kangxi Zidian that are encoded in Unicode 9.0.0/Unihan Database. 63696 characters in total.

The CSV table is encoded in UTF-8, with Windows BOM and EOL marks to facilitate interoperation with Excel.

## 康熙字典筆劃數對照表

在一些傳統場合上，需要根據康熙字典的部首，來計算筆劃數。這有時候會跟手寫筆劃數不同。

例如「華」，手寫計12劃。而康熙字典裏，部首為「艸」，計6劃。加上「艸」部首以外的8劃，共計14劃。

此對照表收錄Unicode 9.0.0/Unihan Database裏所有源自康熙字典的漢字，包括正典和補遺，共計63696字。

CSV格式，UTF8編碼，包含Windows BOM和以CR/LF換行，可直接雙擊或拖放到Excel使用。

[MIT License](https://github.com/breezyreeds/kangxi-strokecount/blob/master/LICENSE)
