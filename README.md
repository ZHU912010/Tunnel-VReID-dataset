# Tunnel-VReID-dataset

Tunnel-VReID is a new dataset constructed to evaluate the tunnel vehicle Re-ID performance. The vehicle images in Tunnel-VReID were captured by 9 pairs of 1920 × 1080 HD surveillance cameras in three different tunnels located at Xi’Han Highway, Shaanxi province, China, which crosses the famous Qinling mountains. Tunnel-VReID dataset includes 1,000 pairs of vehicle identities, which consists of 739 cars, 60 midsize cars (e.g., SUV) and 201 trucks. Because of the severe disturbance of poor light condition, fast motion blur and high between-vehicle similarity, the annotation is rather laborious and has been checked for several times.

With the eighteen cameras, the total time duration of the captured video sequences is 340 minutes. Considering the resolution
of vehicle images, we pick out images of vehicle identities as clear as possible. Each vehicle identity contains two images captured by two non-overlapping cameras. Then we annotate bounding boxes for vehicles in each image that surrounds the whole vehicle body and suppresses the background as much as possible.

Examples of vehicle image pairs from our Tunnel-VReID dataset. The vehicles in tunnels have large intra-variation and little inter-variation. Each column of (a) shows some examples with large intra-variation between same identities of vehicles in each column, and (b) demonstrates some typical vehicles with quite similar appearance but different identities of vehicles in each column. ![image](https://github.com/ZHU912010/Tunnel-VReID-dataset/blob/master/Tunnel-VReID%20dataset.jpg)

The Tunnel-VReID dataset can be downloaded [Here](https://pan.baidu.com/s/1_y4um7atr45Xb1kWNt7zWw).

This dataset proposed in paper [Vehicle re-identification in tunnel scenes via synergistically cascade forests](https://doi.org/10.1016/j.neucom.2019.11.069)
