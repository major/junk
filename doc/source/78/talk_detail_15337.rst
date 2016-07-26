The Challenge and Solution for Glance Image Copy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Abstract:**

In Cloud senario, users uses the same image or images with particular content for the most of the time, sharing and backup will be a common user demand, this needs Glance to be able to provide the ability of copy images. From v1 API to v2 API, Glance have provided this kind of ability in various ways: copy-from, location-add and task-import, all of them have problems more or less, which lead to very bad user experiance of image copy, and Glance service could be unusable in the worst case senario. The Glance team is already aware about this and is trying to provide better functionality through refactor of the provided functionalities. This topic will introduce and discuss how image copy can be done with the current Glance implementation and what are the limitations and cons for each method, what will be modified to provide better user experiences.


* **Xiyuan Wang** *(Xiyuan Wang joined Huawei Technologies Co., Ltd since Jan. 2015. He is one of the developer in OpenStack development team at Huawei, works full-time in OpenStack Community, focuses on Zaqar, Glance and Cinder. He is one of the zaqar core members.)*
