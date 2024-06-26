# poetry-generator

Train a model using TensorFlow to write short poems.

## DATA:
<hr/>

You can get the data used from training from [here](http://www.shakespeares-sonnets.com/all.php). A sample of this data would look like:

```
From fairest creatures we desire increase,
That thereby beauty's rose might never die,
But as the riper should by time decease,
His tender heir might bear his memory:
But thou contracted to thine own bright eyes,
Feed'st thy light's flame with self-substantial fuel,
Making a famine where abundance lies,
Thy self thy foe, to thy sweet self too cruel:
Thou that art now the world's fresh ornament,
And only herald to the gaudy spring,
Within thine own bud buriest thy content,
And, tender churl, mak'st waste in niggarding:
Pity the world, or else this glutton be,
To eat the world's due, by the grave and thee.
```

## Environment and tools Used:
<hr/>

```
1. Jupyter Notebook
2. Numpy
3. Matplotlib
4. Tensorflow
```

## Required package installation:
<hr/>

```
pip install tensorflow==2.1.0
pip install numpy
```

## Results
<hr/>

### Character level 

Training accuracy vs epochs 

<img align="center" alt="Training accuracy vs epochsr"  src="https://raw.githubusercontent.com/PraveenKumarSridhar/poetry-generator/develop/src/Sonnets/Plots/accuracy_plot.png" />

<br/>

Training loss vs epochs 

<img align="center" alt="Training loss vs epochs "  src="https://raw.githubusercontent.com/PraveenKumarSridhar/poetry-generator/develop/src/Sonnets/Plots/loss_plot.png" />
