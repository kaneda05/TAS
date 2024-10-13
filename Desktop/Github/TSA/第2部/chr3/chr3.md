# 第2部　Pythonによる時系列分析の基本
## Pythonによる統計分析の基本
### 統計モデルを推定するライブラリの使用方法
```python
import statsmodels.api as sm
import statsmodels.formula.api as smf
import pmdarima as pm
```
主な使用用途としては、区間推定やt検定・P値の算出


- 1変量データの分析
- 2変量データの分析（数量xカテゴリ）
- 2変量データの分析（数量x数量）