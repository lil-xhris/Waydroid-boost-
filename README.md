# ===============================================================
# Waydroid Gaming Boost (Debian/Ubuntu)
#
# Description:
#   Optimizes Debian (and derivatives) for Waydroid gaming by:
#     - Configuring smart ZRAM (auto size, fast LZ4 compression)
#     - Forcing CPU performance governor + enabling Turbo Boost
#     - Applying GPU tweaks (NVIDIA persistence / AMD / Intel tips)
#     - Boosting Waydroid priority with GameMode
#     - Setting up temperature + performance monitoring
#     - Providing a systemd service for auto persistence at boot
#
# Goal:
#   Smoother gameplay in Waydroid (e.g., Free Fire, PUBG, CODM)
#   on low-end and mid-range Debian laptops and Chromebooks.
#
# Usage:
#   sudo ./waydroid_boost.sh
#   sudo ./waydroid_boost.sh --install-systemd
#
# Author: Chris / GitHub
# License: MIT
# ===============================================================