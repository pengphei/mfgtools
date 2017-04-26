# -*- coding: utf-8 -*-
# @file SConscript
# @brief main building script
# @author Han Pengfei <hanpengfei@autobio.com.cn>
#

Import('genv')

lib_script = "MfgToolLib/SConscript"
lib_files = genv.SConscript(lib_script)
genv.Install(genv["out"], lib_files)

src_script = "TestPrgm/SConscript"
src_files = genv.SConscript(src_script)
genv.Install(genv["out"], src_files)


