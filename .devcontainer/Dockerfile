FROM mcr.microsoft.com/devcontainers/base:ubuntu

RUN apt-get update && apt-get install -y xz-utils neovim tmux

# # Copy starship config to ~/.config/starship.toml
# COPY --chown=vscode:vscode starship/starship.toml /home/vscode/.config/starship.toml
#
# # Copy tmux config directory to ~/.config/tmux
# COPY --chown=vscode:vscode tmux /home/vscode/.config/tmux
#
# # Create a symlink for tmux.conf to ~/.tmux.conf so tmux can find it
# RUN ln -s /home/vscode/.config/tmux/tmux.conf /home/vscode/.tmux.conf
