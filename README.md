# coco-corruption

Misclassified Labels​
- Randomly reassign 10%, 20% 40%, 60% and 80% of object labels to incorrect categories​

Bounding Box Jitter​
- Randomly shift box coordinates generally by either less than 25% or 50% of box width/height using​
- Tested jitter levels: 25% and 50% for 10%, 20% 40%, 60% and 80% of bounding boxes​

Missing Annotations​
- Delete 10%, 20% 40%, 60% and 80% of ground truth boxes​
- Would allow for easy solution to bad labels​

Adding Random Boxes​
- Add random boxes with random classes for 10%, 20%, 40%, 60%, and 80%.​
- Help test how well the model handles false labels​
