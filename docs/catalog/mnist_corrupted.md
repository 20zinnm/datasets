<div itemscope itemtype="http://schema.org/Dataset">
  <div itemscope itemprop="includedInDataCatalog" itemtype="http://schema.org/DataCatalog">
    <meta itemprop="name" content="TensorFlow Datasets" />
  </div>
  <meta itemprop="name" content="mnist_corrupted" />
  <meta itemprop="description" content="MNISTCorrupted is a dataset generated by adding 15 corruptions to the test
images in the MNIST dataset. This dataset wraps the static, corrupted MNIST
test images uploaded by the original authors" />
  <meta itemprop="url" content="https://www.tensorflow.org/datasets/catalog/mnist_corrupted" />
  <meta itemprop="sameAs" content="https://github.com/google-research/mnist-c" />
</div>

# `mnist_corrupted`

MNISTCorrupted is a dataset generated by adding 15 corruptions to the test
images in the MNIST dataset. This dataset wraps the static, corrupted MNIST test
images uploaded by the original authors

*   URL:
    [https://github.com/google-research/mnist-c](https://github.com/google-research/mnist-c)
*   `DatasetBuilder`:
    [`tfds.image.mnist_corrupted.MNISTCorrupted`](https://github.com/tensorflow/datasets/tree/master/tensorflow_datasets/image/mnist_corrupted.py)

`mnist_corrupted` is configured with
`tfds.image.mnist_corrupted.MNISTCorruptedConfig` and has the following
configurations predefined (defaults to the first one):

*   `identity` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: identity

*   `shot_noise` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: shot_noise

*   `impulse_noise` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method:
    impulse_noise

*   `glass_blur` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: glass_blur

*   `motion_blur` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method:
    motion_blur

*   `shear` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: shear

*   `scale` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: scale

*   `rotate` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: rotate

*   `brightness` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: brightness

*   `translate` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: translate

*   `stripe` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: stripe

*   `fog` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: fog

*   `spatter` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: spatter

*   `dotted_line` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method:
    dotted_line

*   `zigzag` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method: zigzag

*   `canny_edges` (`v0.0.1`) (`Size: 235.23 MiB`): Corruption method:
    canny_edges

## `mnist_corrupted/identity`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/shot_noise`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/impulse_noise`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/glass_blur`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/motion_blur`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/shear`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/scale`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/rotate`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/brightness`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/translate`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/stripe`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/fog`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/spatter`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/dotted_line`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/zigzag`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## `mnist_corrupted/canny_edges`

```python
FeaturesDict({
    'image': Image(shape=(28, 28, 1), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

## Statistics

Split | Examples
:---- | -------:
ALL   | 70,000
TRAIN | 60,000
TEST  | 10,000

## Urls

*   [https://github.com/google-research/mnist-c](https://github.com/google-research/mnist-c)

## Supervised keys (for `as_supervised=True`)
`(u'image', u'label')`

## Citation
```
@article{mu2019mnist,
  title={MNIST-C: A Robustness Benchmark for Computer Vision},
  author={Mu, Norman and Gilmer, Justin},
  journal={arXiv preprint arXiv:1906.02337},
  year={2019}
}
```

--------------------------------------------------------------------------------
