# A Transfer Learning-Based Approach to Maritime Warships Re-Identification

## Abstract

Marine vessel re-identification technology is an important component of intelligent shipping systems and an important part of the visual perception tasks required for marine surveillance. However, unlike the situation on land, the maritime environment is complex and volatile, and ships are prone to different degrees of swaying. Warships, as a class of ships, are characterized by fewer image samples and high similarity, and it is more difficult to re-identify warships at sea. Therefore, this paper proposes a dynamic alignment re-identification network model incorporating transfer learning methods. Various types of ships are used as source domain data to assist the network in learning the target domain warships so as to improve the recognition accuracy of warships. At the same time, the swaying situation of warships at sea is simulated and tested to improve the recognition difficulty so as to cope with the impact caused by complex sea conditions. The effect of different types of ships as transfer objects is also discussed. The experimental results show that the improved algorithm improves the mean average accuracy (mAP) by 10.2% and the first hit rate (Rank1) by 4.9% on average.

## Dataset

Table 1. Type and number of vessels in the dataset

| Vessel type     | IDs  | Total Images |
| --------------- | ---- | ------------ |
| Warship         | 24   | 394          |
| Passenger ship  | 23   | 692          |
| Sailboat        | 22   | 870          |
| High speed ship | 21   | 641          |
| Cargo ship      | 22   | 596          |
| Tug             | 6    | 196          |
| Tanker          | 23   | 677          |
| Fishing boat    | 22   | 714          |

Download link: https://drive.google.com/file/d/1QmlaVjQGjexoooJ7yWDV6GWPCqRHnVys/view?usp=share_link
