## Sorting Visualization

Sortings:
  - Bubble (A, D)
  - Insertion (A, D)

installation
```sh
~$ pip3 install -r requirements.txt
```

## possible error on conda env (EndeavourOS, Arch Based)
```sh
libGL error: MESA-LOADER: failed to open iris: /home/<name>/anaconda3/envs/game_env/bin/../lib/libstdc++.so.6: version `GLIBCXX_3.4.29' not found (required by /usr/lib/dri/iris_dri.so) (search paths /usr/lib/dri)
libGL error: failed to load driver: iris
libGL error: MESA-LOADER: failed to open iris: /home/<name>/anaconda3/envs/game_env/bin/../lib/libstdc++.so.6: version `GLIBCXX_3.4.29' not found (required by /usr/lib/dri/iris_dri.so) (search paths /usr/lib/dri)
libGL error: failed to load driver: iris
libGL error: MESA-LOADER: failed to open swrast: /home/<name>/anaconda3/envs/game_env/bin/../lib/libstdc++.so.6: version `GLIBCXX_3.4.29' not found (required by /usr/lib/dri/swrast_dri.so) (search paths /usr/lib/dri)
libGL error: failed to load driver: swrast
X Error of failed request:  BadValue (integer parameter out of range for operation)
  Major opcode of failed request:  152 (GLX)
  Minor opcode of failed request:  3 (X_GLXCreateContext)
  Value in failed request:  0x0
  Serial number of failed request:  99
  Current serial number in output stream:  100
```
solution: https://unix.stackexchange.com/questions/655495/trying-to-run-pygame-on-my-conda-environment-on-my-fresh-manjaro-install-and-ge

