FROM ubuntu:22.04

RUN apt-get update && apt-get install -y xz-utils neovim tmux starship

# Create .config directory for root user
RUN mkdir -p /root/.config

# Copy starship config to ~/.config/starship.toml
COPY ../starship/starship.toml /root/.config/starship.toml

# Copy tmux config directory to ~/.config/tmux
COPY ../tmux /root/.config/tmux

# Create a symlink for tmux.conf to ~/.tmux.conf so tmux can find it
RUN ln -s /root/.config/tmux/tmux.conf /root/.tmux.conf
