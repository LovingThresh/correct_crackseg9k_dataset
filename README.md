# Update

In the future, we intend to build some standard open source models for this dataset, so that subsequent researchers can pay more attention to their own research without worrying about the difficulty of model reproduction and index issues. Please let me know **what type of model** you want to obtain!

Compared with the original paper, our latest experimental results have reached 81%. Therefore, there is still a lot of room for improvement in this data set. Welcome to communicate.

Please share the model and paper you want to reproduce, we can achieve it together!(Office email:SY2113205@buaa.edu.cn)

The plan

- [ ] ResNet (18, 50, 101, 152) with (UNet, DeepLabv3+, SegNet, UperNet)
- [ ] EfficientNet family  with (UNet, DeepLabv3+, SegNet, UperNet)
- [x] ConvNext family  with (UNet, DeepLabv3+, SegNet, UperNet)
- [ ] MobileNet family with (UNet, DeepLabv3+, SegNet, UperNet)
- [ ] VGG family with (UNet, DeepLabv3+, SegNet, UperNet)
- [ ] RepVGG family with (UNet, DeepLabv3+, SegNet, UperNet)
- [ ] SwinVit family
- [ ] MixVit family
- [ ] MobileViT family


# Release Notes

## [download link](https://drive.google.com/file/d/1gRJD-RQluCh3YDLxwSN1tdG1U3Z2hqq7/view?usp=sharing)

First of all, we would like to thank the original authors for their [work](https://arxiv.org/abs/2208.13054), but there are certain problems in the released datasets. So, this work corrects their datasets.

Based on the provided mask data, we found the corresponding image data from [the original combined dataset](https://github.com/khanhha/crack_segmentation). All images and masks can be matched in the new dataset.

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
