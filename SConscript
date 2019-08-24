target = 'ShellLink'

files = Split("""
	ShellLink.cpp
""")

resources = Split("""
	Resource.rc
""")

libs = Split("""
	kernel32
	ole32
	uuid
	user32
""")

examples = ''

docs = Split("""
	Readme.html
""")

Import('BuildPlugin')

BuildPlugin(target, files, libs, examples, docs, res = resources)