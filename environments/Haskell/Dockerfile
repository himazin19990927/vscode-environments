FROM buildpack-deps:bullseye

RUN curl --proto '=https' --tlsv1.2 -sSf https://get-ghcup.haskell.org | sh
ENV PATH=${PATH}:/root/.cabal/bin:/root/.ghcup/bin

RUN ghcup install hls