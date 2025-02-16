# online feature selection by balancing cost and precision
## 解读
### Online Feature Selection
强调特征选择是一个在线(Online)过程，这意味着算法需要随着数据的不断到来，动态地选择特征。这与传统的离线特征选择方法不同，更适用于实际应用场景。

### Balancing Cost and Precision
强调在特征选择过程中，需要在“成本”(Cost)和“精度”(Precision)之间进行权衡。
- **Cost(成本)**：
  - **特征获取成本**：某些特征的获取可能需要花费额外的资源或金钱(例如：用户隐私信息、昂贵的传感器数据等)。
  - **计算成本**：使用更多特征会增加模型的计算复杂度，降低预测速度。
- **Precision(精度)**：模型预测准确率：特征选择的目标是选择最相关的特征，提高模型的预测准确率。 
