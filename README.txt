-=(Pleiads_Senhor notes)=-

Tested: Working Video 720p, 1080p & Sound

---------------------------------------------------------------------------------
-- 
-- Arcade: Pleiads port to MiSTer by Sorgelig
-- 22 October 2017
-- 14 June  2019 - renamed and load Capitol ROM for Capitol version (From Phoenix)
---------------------------------------------------------------------------------
-- Phoenix (Amstar) FPGA - DAR - 2016
-- http://darfpga.blogspot.fr
---------------------------------------------------------------------------------
-- 
-- Support screen and controls rotation on HDMI output.
-- Only controls are rotated on VGA output.
-- 
-- 
-- Keyboard inputs :
--
--   F3          : Add coin
--   F2          : Start 2 players
--   F1          : Start 1 player
--   SPACE       : Fire  
--   UP/RIGHT    : Move up 
--   DOWN/LEFT   : Move down
--   CTRL        : Barrier(Shield)
--
-- MAME/IPAC/JPAC Style Keyboard inputs:
--   5           : Coin 1
--   6           : Coin 2
--   1           : Start 1 Player
--   2           : Start 2 Players
--   D,G     : Player 2 Movements
--   A           : Player 2 Fire
--   S           : Player 2 Barrier(Shield)
--
-- Joystick support.
-- 
-- 
---------------------------------------------------------------------------------


                                *** Attention ***

ROMs are not included. In order to use this arcade, you need to provide the
correct ROMs.

To simplify the process .mra files are provided in the releases folder, that
specifies the required ROMs with checksums. The ROMs .zip filename refers to the
corresponding file of the M.A.M.E. project.

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for
information on how to setup and use the environment.

Quickreference for folders and file placement:

/_Arcade/<game name>.mra
/_Arcade/cores/<game rbf>.rbf
/_Arcade/mame/<mame rom>.zip
/_Arcade/hbmame/<hbmame rom>.zip
