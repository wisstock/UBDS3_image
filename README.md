Bio Data Science^3 
==================
_Biological Data Science Summer School. 2-14 July 2023, Uzhhorod, Ukraine._

Матеріали до практичного курсу з аналізу даних зображень "Реконструкція біофізичних властивостей кальцій-зв'язуючих білків за результами конфокальної мікроскопії".

### Необхідні бібліотеки
- Python >= 3.9
- Jupyter
- Numpy
- Scipy
- Scikit-image
- Matplotlib
- SymPy (optional, for section 1 only)

Наполегливо рекомендую використовувати менеджер середовищ для встановлення бібліотек щоб запобігти конфлікту версій та залежностей ([Miniconda](https://docs.conda.io/en/latest/miniconda.html), [venv](https://docs.python.org/3/library/venv.html) і т.д.), інструкція для роботи з Conda наведена нижче.


### Встановлення Conda та створення середовища
[Встановіть](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) __Miniconda__ (Anaconda одразу містить купу непотрібних для даного проекту пакетів і займай 3GB) для Вашої операційної системи. Настуані команди вводити в Unix-термінал (у випадку Linux або MacOS) або у конда Conda PowerShell (у випадку Windows).

Створення середовища із YAML файла:
```
conda env create -f bds3_env.yml
```

Запуск середовища:
```
conda activate bds3_env
```

Вихід з середовища:
```
conda deactivate bds3_env
```


### Корисні посилання
- [Scikit-image examples](https://scikit-image.org/docs/stable/auto_examples/index.html)
- [Image processing learning resorces](https://homepages.inf.ed.ac.uk/rbf/HIPR2/hipr_top.htm)
- [Scientific Volume Imaging](https://svi.nl/Huygens-Imaging-Academy)
- [Introduction to Modeling for Neuroscience](https://dabane-ghassan.github.io/ModNeuro/)
- [Convolutions in image processing, YouTube](https://www.youtube.com/watch?v=8rrHTtUzyZA)


### Література
- __Fundamentals of Fluorescence Imaging__

  Cox, [doi.org/10.1201/9781351129404 ](https://www.taylorfrancis.com/books/edit/10.1201/9781351129404/fundamentals-fluorescence-imaging-guy-cox)
- __Handbook of Biological Confocal Microscopy__

  Pawley, [doi.org/10.1007/978-0-387-45524-2](https://link.springer.com/book/10.1007/978-0-387-45524-2)
- __Enzyme Kinetics: Principles and Methods__

  Bisswanger, [DOI:10.1002/9783527806461](https://onlinelibrary.wiley.com/doi/book/10.1002/9783527806461)
- __Calcium Signaling in Dendrites and Spines: Practical and Functional Considerations__

  Higley & Sabatini, [DOI 10.1016/j.neuron.2008.08.020](https://pubmed.ncbi.nlm.nih.gov/18817730/)
- __Competitive Calcium Binding: Implications for Dendritic Calcium Signaling__

  Markram, [doi.org/10.1023/A:1008891229546](https://link.springer.com/article/10.1023/A:1008891229546)
- __Decoding glutamate receptor activation by the Ca2+sensor protein hippocalcin in rat hippocampal neurons__

  Dovgan et al., [doi:10.1111/j.1460-9568.2010.07303.x](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1460-9568.2010.07303.x)