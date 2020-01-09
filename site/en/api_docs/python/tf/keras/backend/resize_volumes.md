page_type: reference
<style>{% include "site-assets/css/style.css" %}</style>

<!-- DO NOT EDIT! Automatically generated file. -->

# tf.keras.backend.resize_volumes


<table class="tfo-notebook-buttons tfo-api" align="left">

<td>
  <a target="_blank" href="https://github.com/tensorflow/tensorflow/tree/r2.0/tensorflow/python/keras/backend.py#L2834-L2863">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td></table>



Resizes the volume contained in a 5D tensor.

### Aliases:

* `tf.compat.v1.keras.backend.resize_volumes`
* `tf.compat.v2.keras.backend.resize_volumes`


``` python
tf.keras.backend.resize_volumes(
    x,
    depth_factor,
    height_factor,
    width_factor,
    data_format
)
```



<!-- Placeholder for "Used in" -->


#### Arguments:


* <b>`x`</b>: Tensor or variable to resize.
* <b>`depth_factor`</b>: Positive integer.
* <b>`height_factor`</b>: Positive integer.
* <b>`width_factor`</b>: Positive integer.
* <b>`data_format`</b>: One of `"channels_first"`, `"channels_last"`.


#### Returns:

A tensor.



#### Raises:


* <b>`ValueError`</b>: if `data_format` is neither
    `channels_last` or `channels_first`.