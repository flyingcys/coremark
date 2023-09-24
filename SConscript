from building import *

cwd     = GetCurrentDir()
src     = Glob('*.c') + Glob('*.cpp')
src     += ['rt-thread/core_portme.c']

CPPPATH = [cwd]
CPPPATH += [cwd + r'/rt-thread']

group = DefineGroup('CoreMark', src, depend = [''], CPPPATH = CPPPATH)

Return('group')
