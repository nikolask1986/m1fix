RUN wget -O "/usr/local/bin/go-replace" "https://github.com/nikolask1986/m1fix/raw/master/gr-arm64-linux" \
    && chmod +x "/usr/local/bin/go-replace" \
    && "/usr/local/bin/go-replace" --version
