# ORPHANED TidalCycles Arch Support Branch

It is unfortunately not possible to support arch when it will allow packaging installation without adequately specifying dependencies (yes, you can cleanly install a package via `pacman` then have it fail to start because of missing dependencies)

Leaving this here in case anyone else wishes to try and take on the support.

# Please Note!

This role will clobber your existing .vimrc, but it will take a timestamped backup beforehand.

Plug is used for plugin management

I may make it a bit smarter in the future to at least attempt to insert the tidal-vim plugin if the Plug framework is already being used.


