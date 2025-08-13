# coco-corruption

### Misclassified Labels​
Randomly reassign 10%, 20% 40%, 60% and 80% of object labels to incorrect categories​
<img width="789" height="509" alt="Image" src="https://github.com/user-attachments/assets/51fc5aa9-a90c-42b4-a2b5-67083f71a82b" />

### Bounding Box Jitter​
Randomly shift box coordinates generally by either less than 25% or 50% of box width/height using​
Tested jitter levels: 25% and 50% for 10%, 20% 40%, 60% and 80% of bounding boxes​
<img width="722" height="470" alt="Image" src="https://github.com/user-attachments/assets/a16c6947-4065-47c3-b17a-6a89884edb0c" />
### Missing Annotations​
Delete 10%, 20% 40%, 60% and 80% of ground truth boxes​
Would allow for easy solution to bad labels​
<img width="1431" height="458" alt="image" src="https://github.com/user-attachments/assets/f7d2ffa5-4414-4ada-a72b-273849fa138c" />

### Adding Random Boxes​
Add random boxes with random classes for 10%, 20%, 40%, 60%, and 80%.​
Help test how well the model handles false labels​
<img width="657" height="490" alt="image" src="https://github.com/user-attachments/assets/6694a6a5-c689-4f9b-a951-47b7eb00b633" />
