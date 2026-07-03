# MergeBOM Algorithm

## Input

BOM
BOM_Assy

## Output

BOM_Final

## Rule

BOMはメインFCStd内数量

BOM_Assyは親子関係

親数量を利用して子数量へ伝播する

多段Assy対応

循環参照禁止

Parentは最終出力から除外
