# Abortion-Facebook-Dataset-US

The dataset has been collected for the project "Analyzing the Stance of Facebook Posts on Abortion Considering State-level
Health and Social Compositions" (https://arxiv.org/abs/2305.09889).

The data in this study has been collected by using CrowdTangle (https://www.crowdtangle.com/) and a keyword "abortion" for each state in the US to gather insights into the attitudes toward abortion at the state level in the US. In more detail, we use this keyword, along with the specified time frame by also specifying each state in the US (e.g. we collect posts for Alabama, then for Alaska, then for Arkansas, etc.). The time range selected was from May 4 to June 30, 2022, after the leak of the Supreme Court’s decision to overturn Roe V. Wade.
The total number of posts collected from public pages was 82,056, while the number of posts from public groups was 13,923.

The page_ids.csv includes a list Facebook IDs of the pages found in our dataset that has be to supplemented to CrowdTangle API to replicate our dataset.
The group_ids.csv includes a list Facebook IDs of the groups found in our dataset that has be to supplemented to CrowdTangle API to replicate our dataset.
Note that the exact same keyword, locations, and time frame need to be specified to the API in order to obtain the same data.

If you use this dataset in your study, please cite our paper:

@article{aleksandric2023analyzing,

  title={Analyzing the Stance of Facebook Posts on Abortion Considering State-level Health and Social Compositions},
  
  author={Aleksandric, Ana and Anderson, Henry Isaac and Dangal, Anisha and Wilson, Gabriela Mustata and Nilizadeh, Shirin},
  
  journal={arXiv preprint arXiv:2305.09889},
  
  year={2023}
}


