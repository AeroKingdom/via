release: git clone https://github.com/pyenv/pyenv.git ~/.pyenv; chmod +x /app/; echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile; echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile; echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.bash_profile; exec "$SHELL"; 
web: make dev
