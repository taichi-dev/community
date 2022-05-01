#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; UNLEASH CREATIVITY WITH VOXEL 2022

> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Opens: Friday 29th April 2022 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Closes: Wednesday 25th May 2022

## Introduction

Taichi Lang is embedded in Python and therefore its renderers can run on any operating system and interact with Python seamlessly. One day, the duo of Yuanming and Ye, the co-founders of Taichi Graphics, put together a GPU-based light tracing voxel renderer on their way back. It then occurred to them that, given that Taichi Lang v1.0.0 was released, they can take the initiative to organize a Taichi Lang-based voxel challenge that is free to enter and open to voxel art lovers from all over the world.

Voxel Challenge 2022 takes place from 29th April 2022 to 25th May 2022. The competition is for original, ingenious, and Taichi Lang-based voxel artworks. The idea is to unleash creativity, so the entries can be on any subject, in any style. The participants are required to complete their voxel entries within 99 lines of Taichi Lang code and submit them before the submission deadline. The Taichi Lang community votes for the winner and runners-up, and the Voxel Challenge Committee (VCC) selects from all entries five Committee's Picks. 

## Challenge

The participants of Voxel Challenge 2022 are required to come up with original, inspiring voxel artworks in less than 99 lines of Taichi Lang code. The participants can decide freely on the topics, styles, and material (voxel or light source) to use, so long as their entries are in line with the competition's [Terms and Conditions](#terms-and-conditions). 

### Submission Criteria

- The submission deadline is *2:00 AM PDT 18th May 2022*. Submissions sent after this deadline will not be considered. 
- By submitting their voxel entries the participants agree to the [Terms and Conditions](#terms-and-conditions). 
- See [How to Submit](#how-to-submit) for more information on entry submission. 

### API Usage

Only the following five APIs can be used：

```python
scene = Scene(voxel_edges=0.06, exposure=3)
# voxel_edges: The width of each voxel's edge. You can set it to 0. 
# exposure: The exposure value, which prevents overexposure or underexposure of the image. 

scene.set_voxel(voxel_index, mat, color)
# voxel_index: A tuple of three integers specifying the postion of the voxel.
#   The Voxel Challenge participants can use floating-point numbers as index for convenience.
#   But note that (3.5, 10.9, 20.2) will be rounded to (4, 11, 20).
#   Valid range of voxel_index: [-64, 63] x [-64, 63] x [-64, 63].
#   Undefined behavior may occur if your input is out of this range. 
#
# mat (material) has the following settings:
#   0: The voxel does not exist (You can use this setting to delete the voxel).
#   1: A voxel that does not emit light.
#   2: A voxel that emits light.
# 
# color: A 3D vector. Its components are real numbers in the range [0.0,1.0] and converted to uint8 (0~255) during accessing. 

mat, color = scene.get_voxel(voxel_index)
# Retrieves the material and color of a specified voxel. 
#
# voxel_index: A tuple of three integers specifying the postion of the voxel.
#   The Voxel Challenge participants can use floating-point numbers as index for convenience.
#   But note that (3.5, 10.9, 20.2) will be rounded to (4, 11, 20).
#   Valid range of voxel_index: [-64, 63] x [-64, 63] x [-64, 63].
#   Undefined behavior may occur if your input is out of this range. 
#
scene.set_floor(height=0, color=(r, g, b))
# Sets the height and color of the floor. The floor has normal vector in the y direction
# 
# color: A 3D vector. Its components are real numbers in the range [0.0,1.0] and converted to uint8 (0~255) during data access. 

Scene.set_directional_light(direction, direction_noise, color)
# Sets the direction of parallel light. 
# See https://github.com/taichi-dev/voxel-challenge/blob/main/example4.py. 
#
# direction_noise: Sets the softness of the shadow (how easily it blends with the background).
# 
# color: A 3D vector. Its components are real numbers in the range [0.0,1.0] and converted to uint8 (0~255) during accessing. 

scene.set_background_color(color)
# Sets the background color. 
# 
# color: A 3D vector. Its components are real numbers in the range [0.0,1.0] and converted to uint8 (0~255) during accessing. 
```

### Size Criteria

- Each participants is given a 128x128x128 voxel grid: 
  - The x, y, or z coordinate of the voxel grid is in the range [-1, 1]; the size of each voxel is 1/64.
  - Note that the index of x, y, or z coordinate starts off from `-64` and ends at `63`. 
- The total number of your code lines must not exceed 99; the number of characters in each line must not exceed 120.

### Screen Capture

- To capture your voxel artwork, you can press **P** after moving your camera and your screenshot appears in the **screenshots** folder.
- The submitted screenshot must be raw and original. Photo editing tools such as Photoshop are not allowed.

### Other Requirements

- The participants cannot create new fields or import libraries other than **scene**, **taichi**, and **taichi.math**. 
- File I/O is not allowed.

## Calendar

| **Date** | **Description** |
| ------------------- | ------------------------------------------------------------ |
|**29th April 2022**| Day one. Submission of voxel artwork begins. <img width=380/>|
| **18th May 2022**  | The submission deadline is *2:00 AM PDT 18th May*. <img width=380/>|
| **18th May 2022**  | The community begins to vote from *7:00 PM PDT 18th May*. <img width=380/>|
| **24th May 2022**  | The voting deadline is *2:00 AM PDT 24th May*. <img width=380/>|
| **25th May 2022**  | The VCC announces the winning entries.  <img width=380/>       |

## Prizes

In this competition, the Taichi Lang community votes for the entries on GitHub. The winning entries are those who receive the most votes from the community. Committee's Picks will be selected by the VCC. 

| **FIRST PRIZE** *x1* | **SECOND PRIZE** *x1* | **THIRD PRIZE** *x2* |
| :------------------: | :-------------------: | :------------------: |
|   Nintendo Switch <img width=250/>   |  Beats Fit Pro <img width=250/>      |  LEGO toy  <img width=250/>         |

|                  **Committee's Picks** *x5*                  |
| :----------------------------------------------------------: |
| Committee's Picks will receive a bag with a photoprint of their artwork.<img width=500/> |

|                   **Contribution Awards**                    |
| :----------------------------------------------------------: |
| All participants will receive a tailor-made T-shirt and a box of tailor-made facial masks.<img width=400/> |

|                      **Special Gifts**                       |
| :----------------------------------------------------------: |
| <p>Participants who post their artwork on social media like Twitter will receive a tailor-made postcard with a photoprint of their artwork. Remember to tag us <b>@TaichiGraphics</b> with the hashtag <b>#voxelchallenge</b> in the post.</p><p>Participants who write a blog about their voxel entries will receive a tailor-made thermos cup.</p> |

## How to Submit

The participants can submit and update their voxel artwork from 29th April to 2:00 AM PDT 18th May. 

1. Create a repo for hosting your voxel artwork:

   1.1 Go to the [template repo](https://github.com/taichi-dev/voxel-challenge/).
   1.2 Click the green **Use this template** button to copy your own new repo from the template repo.
   1.3 Make your repo public. 
   1.4 Update **main.py** (the source code) and **READNE.md** to your own version, ensuring that your work is in line with the [Terms and Conditions](#terms-and-conditions).
   1.5 If you have more than one entries, save the corresponding source code in other **.py** files. 

2. Submit your entry by leaving a comment to [this issue](https://github.com/taichi-dev/voxel-challenge/issues/11) with the following mandatory information:

   - The name of your entry.
   - A link to your repo.
   - A screenshot of your voxel artwork. 

3. If your have more than one entries to submit, submit each one of them as a separate comment to the above issue. 

> **Tips**: Please join [our Slack channel](https://join.slack.com/t/taichicommunity/shared_invite/zt-14ic8j6no-Fd~wKNpfskXLfqDr58Tddg) for any queries or to receive the latest news from Voxel Challenge 2022.

## How to Vote 

Everyone from the Taichi Lang community is eligible to vote. The voting begins at *18th May* and ends on *24th May*. You can respond to the entries that are to your liking with emoji. The VCC will release the emoji valid for the votes after the submission deadline.

> **Tips**: Please join [our Slack channel](https://join.slack.com/t/taichicommunity/shared_invite/zt-14ic8j6no-Fd~wKNpfskXLfqDr58Tddg) for any queries or to receive the latest news from Voxel Challenge 2022.

## Frequently Asked Questions

### Q: Can I update my artwork after submission?

You can, so long as it is before the submission deadline (19th May). You may also want to update the screenshot if it is changed. 

### Q: Can I submit more than one piece of voxel artwork?

You can. Simply submit your other entry by leaving a separate comment to the issue. Only use one GitHub repo to host all your voxel artwork. 

### Q: Where could I post a blog about my artwork and how do I let you know?

You can post your blog on [Medium](www.medium.com), [Reddit](https://www.reddit.com/), or any public platform. Send us the link to your blog through [Slack](https://join.slack.com/t/taichicommunity/shared_invite/zt-14ic8j6no-Fd~wKNpfskXLfqDr58Tddg) or by mailing to: <community@taichi.graphics>.

### Q: How do I keep up to date with the competition?

All information about Voxel Challenge 2022 will be broadcasted with the hashtag **#voxel-challenge** in our [Slack channel](https://join.slack.com/t/taichicommunity/shared_invite/zt-14ic8j6no-Fd~wKNpfskXLfqDr58Tddg). Welcome to join this channel for the latest news from the competition!

## Terms and Conditions

- Each participant must guarantee the authorship and originality of his/her voxel artwork in the first place. 
- Participants shall be accountable for the artwork they submit and it not infringe any third-party intellectual rights. If plagiarism or infringement is identified in their submissions, the participants will be disqualified immediately and shall bear all the consequences. 
- By submitting their entries the participants agree to authorize the organizer to use their artwork in specific media outlets for promotion purposes.
- All entries must follow the [Code of Conduct of the Taichi Lang community](https://github.com/taichi-dev/taichi/blob/master/CODE_OF_CONDUCT.md).
- The VCC reserves the right to reject disputable entries, and the committee reserves the right to the final interpretation of these terms and conditions. 

## Contact us

- [Slack channel](https://join.slack.com/t/taichicommunity/shared_invite/zt-14ic8j6no-Fd~wKNpfskXLfqDr58Tddg), **#voxel-challenge**.
- Email: <community@taichi.graphics>
