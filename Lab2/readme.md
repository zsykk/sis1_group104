3.1

# Write the code here!git clone https://github.com/zsykk/sis1_group108.git
filepath = "ukele_sound.wav"
ref, fs = load_audio(filepath)


T_0 = 1/147
plot_signals(ref, fs, 0.7406161, 0.7406161+7*T_0)
