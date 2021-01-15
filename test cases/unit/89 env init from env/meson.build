project('env init from env')

base_env = environment()
base_env.set('IN_BASE', 'true')

new_env = environment(base_env)
new_env.set('IN_NEW', 'true')

test('check env', find_program('script.py'), env: new_env)
