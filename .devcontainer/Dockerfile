FROM golang:1.21.1-bullseye
RUN go install golang.org/x/tools/gopls@latest \
    && go install -v honnef.co/go/tools/cmd/staticcheck@latest
