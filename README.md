# Edu-x: an AI teaching evaluation app.

EduX是一款基于面部识别和表情识别，来对课堂进行多维度评价的追踪评估软件。在用户上传课程的录像后、EduX会每隔数秒抽取视频中的一帧，并使用YOLO V3来提取其中的人脸。需要注意的是，EduX绝对不会去追踪任何一位同学。因为我们的目标是对整个课程进行量化分析，所以EduX统计的是每一帧的所有同学里笑/打哈欠/闭眼的比例。在对所有抽取的帧进行如上分析之后，EduX会以生成line chart形式来展示上述的笑、瞌睡等表情在整节课上的变化趋势。最后，EduX会通过上述表情的比例和趋势计算出课堂趣味性、课程难度、学生专注度、课堂活跃度、及课堂体验两极分化程度这五项复合指标， 并以这些指标生成对整节课的体验进行量化的雷达图。
