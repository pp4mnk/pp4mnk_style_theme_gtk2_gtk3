pp4mnk_style 1.1
EasyOS Excalibur 7.5 · GTK 2, GTK 3, JWM and ROX-Filer
====================================================

1. Unzip the download and open pp4mnk_style-1.1.pet in ROX-Filer.
   Confirm in PKGget.
2. Open the GTK/Qt theme chooser (Chtheme), or run
   gtk_chtheme_wrapper in a terminal. Select PP4MNK-Light or
   PP4MNK-Dark and click Apply. Reopen apps to refresh GTK styling.
3. In EasyJWM's window-border theme chooser, select pp4mnk-style.
4. In the wallpaper chooser (qwallpaper), select
   pp4mnk-style-night-road.png. The PET installs it in
   /usr/share/backgrounds. An original 1672 × 941 copy is in the ZIP.
5. In a terminal as root, run 'pp4mnk-style-icons apply' to activate
   the drive icons. Save work and use Restart X to reload ROX. For
   discs already present, 15 PNGs are supplied across drive, USB, SD,
   optical and floppy variants. Lavender represents an unmounted
   device, cyan represents a mounted device and a lock represents
   a mounted device which cannot be unmounted from the desktop.
   The icons appear on the ROX-managed desktop.

Optional Conky (requires an existing Conky installation):
   conky -c /usr/share/pp4mnk-style/conky.conf
   Quit with Ctrl+C. It shows RAM, used/total ZRAM swap and the qfix
   boot argument when available. Copy the configuration to adjust
   its position via gap_x and gap_y.

To go back, choose your previous GTK theme, JWM theme and wallpaper.
Then run 'pp4mnk-style-icons restore' if you applied the drive icons,
and use Restart X. Restore the styles before uninstalling the PET.
Version 1.0 has its own theme name and can coexist with this pack.
Save your session at shutdown if you use RAM mode and want to keep
the changes.

GTK 2 uses the Pixbuf/Pixmap engine. GTK 3 requires version 3.20+
of GTK 3. The pp4mnk GTK theme is based on Eucalypt by 01micko (2011).
The original wallpaper was supplied for this edition.
