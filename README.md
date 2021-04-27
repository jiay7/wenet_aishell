# wenet_aishell
添加了data augment部分代码的recipe
主要改动的地方在wenet/dataset/dataset.py和wav_distortion.py
另外在conf/*.yaml中添加了参数：
  augment: true
  musan_path: "/home/caidanwei/musan/"
  rir_path: "/home/caidanwei/RIRS_NOISES/simulated_rirs/"
