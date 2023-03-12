# Revision_Surgery



## Neural Network Model Starter Code
To load the model, run the following in the command line:
```
pip install pyyaml h5py
new_model = tf.keras.models.load_model('revision_model.h5')
```
where "num" is an integer or a float, and [0,1] represents a categorical variable, where 0 = no, and 1 = yes

After loading the model, run the following to generate a probability prediction:
```
new_model.predict(dict(test))
```

### Output Format
>**value <= 0.5: Revision Surgery Unlikely, otherwise: Revision Surgery Likely**

### Python Version
>3.7.4

