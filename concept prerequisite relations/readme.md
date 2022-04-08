### Concept prerequisite relations

- *A -> B*： A is a prerequisite of B.
- *None*：A is **not** a prerequisite of B.

### Datasets adjustment

- **CrowdComp**: We adjust the original data set label to 2 classification, the original data set to 3 classification.
- **MOOC dataset**: We only use datasets W-DSA and W-ML containing Wikipedia concept pairs.
- **LectureBank**: The original LectureBank dataset contains 208 topics. therefore, we remove concept pairs with concept index > 208 in the prerequisite relation pairs.