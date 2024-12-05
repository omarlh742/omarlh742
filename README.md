from inference import Predictor

predictor= Predictor(
    'hayao:v2',
    # if set True, generated image will retain original color as input image
    retain_color=True
)

url = 'https://github.com/ptran1203/pytorch-animeGAN/blob/master/example/result/real/1%20(20).jpg?raw=true'

predictor.transform_file(url, "anime.jpg")
