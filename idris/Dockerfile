from mitchty/alpine-ghc

run apk update && \
    apk add ncurses-dev gmp-dev libffi-dev && \
    cabal update && \
    cabal install idris -f gmp -f ffi -f gmp

workdir /tmp
cmd ["bash"]
