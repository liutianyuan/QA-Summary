# 项目一：摘要自动生成

## 环境
Python3.6

The conflict is caused by:
    The user requested numpy==1.18.5
    gensim 3.8.3 depends on numpy>=1.11.3
    matplotlib 3.3.4 depends on numpy>=1.15
    pandas 1.1.5 depends on numpy>=1.15.4
    scikit-learn 0.24.1 depends on numpy>=1.13.3
    tensorflow 2.4.1 depends on numpy~=1.19.2

To fix this you could try to:
1. loosen the range of package versions you've specified
2. remove package versions to allow pip attempt to solve the dependency conflict
