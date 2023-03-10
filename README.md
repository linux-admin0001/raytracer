# raytracer

## My own raytracer in one week
Requirements: `pillow`, `PyGLM`

## How to use?
1. `git clone https://github.com/linux-admin0001/raytracer.git`
2. `cd raytracer`
3. `python -m pip install PyGLM pillow tqdm`
4. `python main.py`
5. Enjoy!

## Gallery
![rendered](https://user-images.githubusercontent.com/73735838/220148976-319028c6-5e05-40ab-af04-9f397cf3a971.png)
![five_shperes_and_mirror](https://user-images.githubusercontent.com/73735838/220149540-465ef181-8e33-4b64-831a-13d245576e4e.png)
![one_shpere_with_ideal_mirror_floor](https://user-images.githubusercontent.com/73735838/220149571-6a06834e-6b05-4184-8b75-eeba0c0e47f6.png)
![other_shpere](https://user-images.githubusercontent.com/73735838/220149615-be9ae5a5-b661-4e37-ad38-7f8a444c6202.png)
![rendered](https://user-images.githubusercontent.com/73735838/220170421-2a20fa82-98b0-4f52-80fe-f4a91ddae257.png)
![rendered](https://user-images.githubusercontent.com/73735838/220175234-b69bcc2f-292d-4b90-aad7-f1e7976169cd.png)
![rendered](https://user-images.githubusercontent.com/73735838/220177127-e4d74685-ddc9-45d8-8ff7-759e7c36d850.png)
#### Perfectly polished metal surface (blur ratio: 0)
![rendered](https://user-images.githubusercontent.com/73735838/220428677-08edc0c2-7b52-49e1-82e8-85ae870af9b2.png)
#### Blurred reflections (0 secondary reflected rays to suppress noise, blur ratio: 0.5)
![rendered](https://user-images.githubusercontent.com/73735838/220428112-7abe0b66-e570-40ca-a60b-0e8f6e19f727.png)
#### Blurred reflections (20 secondary reflected rays to suppress noise, blur ratio: 0.5)
![rendered](https://user-images.githubusercontent.com/73735838/220426765-cb4d11a0-3bcd-46b1-87c8-def5267e996e.png)
#### Blurred reflections (20 secondary reflected rays to suppress noise, blur ratio: 0.1)
![rendered_](https://user-images.githubusercontent.com/73735838/220432175-2799064a-1cbe-4585-b684-619a1ae0356b.png)

## Todo
* add rotation matrix
* add blurry reflection
* add visibultity light sources
