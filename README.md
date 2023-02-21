# Release Notes

## [download link](https://drive.google.com/file/d/1gRJD-RQluCh3YDLxwSN1tdG1U3Z2hqq7/view?usp=sharing)

First of all, We would like to thank the original authors for their [work](https://arxiv.org/abs/2208.13054), But there are certain problems in the released datasets. This work corrects their datasets

Based on the provided mask data, we found the corresponding image data from the original combined dataset. All images and masks can be matched in the new dataset.

## Document Description

Note: All files have the suffix '.png'.

### Original

1. Images(original)
2. Masks(original)
3. meta_data.csv(original)

-------------------------------

### New

1. img_dir(new)
   1. train(new, 90%, shuffle)
   2. val(new, 5%, shuffle)
   3. test(new, 5%, shuffle)
2. ann_dir(new)
   1. train(new, 90%, shuffle)
   2. val(new, 5%, shuffle)
   3. test(new, 5%, shuffle)
3. new_meta_data.csv(new)
