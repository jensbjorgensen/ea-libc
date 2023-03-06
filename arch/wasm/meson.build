# WASM architecture meson build

wasm_arch_dep = declare_dependency(
	include_directories: include_directories('include'),
	sources: files(
	)
)

if build_arch == 'wasm'
	build_machine_dep = wasm_arch_dep
endif

if host_arch == 'wasm'
	host_machine_dep = wasm_arch_dep
endif
