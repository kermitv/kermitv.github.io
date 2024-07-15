FROM mcr.microsoft.com/vscode/devcontainers/ruby:0-3.1

# Install Jekyll and Bundler
RUN gem install jekyll bundler

WORKDIR /workspace

EXPOSE 4000

CMD ["jekyll", "serve", "--host", "0.0.0.0"]
