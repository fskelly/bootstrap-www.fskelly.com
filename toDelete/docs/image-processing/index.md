# +++
# title = "Image Processing"
# description = "Guide to resize and align images"
# date = 2021-08-15T14:19:06+08:00
# draft = false
# comment = true
# toc = true
# reward = true
# carousel = true
# categories = [
#   "Markdown"
# ]
# tags = [
#   "Image"
# ]
# series = [
#   "Docs"
# ]
# aliases = [
#   "/en/posts/image-processing"
# ]
# [menu.footer]
#   parent = "features"
#   weight = 2
# +++
# 
# This article offers some use cases for showing how to resize and align images.
# <!--more-->
# 
# ## Resizing Images
# 
# We use the URL query of image for resizing images. For example:
# 
# ### Specify the width and preserve ratio
# 
# ```markdown
# ![Resize](featured-sample.png?width=300px)
# ```
# 
# ![Resize](featured-sample.png?width=300px)
# 
# ### Specify the height and preserve ratio
# 
# ```markdown
# ![Resize](featured-sample.png?height=200px)
# ```
# 
# ![Resize](featured-sample.png?height=200px)
# 
# ### Specify the width and height
# 
# ```markdown
# ![Resize](featured-sample.png?width=300px&height=200px)
# ```
# 
# ![Resize](featured-sample.png?width=300px&height=200px)
# 
# > It can be used not only for [page resources](https://gohugo.io/content-management/page-resources/), but also for the # **static** images and external images. 
# > However, in addition to page resources, others are resized by inline style, that is, their original size will not change.
# 
# ## Aligning Images
# 
# We can easily align images by adding URL fragments. Such as `#center`, `#floatleft` and `#floatright` represents align # center, float left and float right respectively.
# 
# ### Center
# 
# Adding the `#center` fragment for aligning images to the center.
# 
# For example: `![Center](/featured-sample.png#center)`.
# 
# ![Center](/featured-sample.png?height=120px#center)
# 
# ### Float Left
# 
# ![Float Left](/featured-sample.png?height=120px#floatleft)
# 
# Adding the `#floatleft` fragment for floating images to the left.
# 
# For example: `![Float Left](/featured-sample.png#floatleft)`.
# 
# ### Float Right
# 
# ![Float Right](/featured-sample.png?height=120px#floatright)
# 
# Similarly, we can also float images to the right by adding the `#floatright` fragment.
# 
# For example: `![Float Right](/featured-sample.png#floatright)`.
# 