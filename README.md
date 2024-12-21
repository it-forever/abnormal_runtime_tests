# abnormal_runtime_tests
run tests runtime: qemu-kvm, firecracker (more modification kernel), containerd

[example run firecracker](./firecracker_tests/Readme.md)

Test:

- [benchmark_docker](./benchmarks/docker.md)

- [benchmark_qemu](./benchmarks/kvm.md)

- [benchmark_firecracker_disable_virtualization_and_part_cve](./benchmarks/fc.md)

- [benchmark_firecracker_part2_disable_settings_for_cpu](./benchmarks/fc-part2.md)

- [description_run_test_clickhouse](./benchmarks/manual_benchmark.md)


Kernels 6.8.0-49:

- [default_kernel_for_fc](./kernel_config/default-fc-config)

- [firecracker_disable_virtualization_and_part_cve](./kernel_config/mod-fc-config)

- [firecracker_part2_disable_settings_for_cpu](./kernel_config/mod-fc-config-max-perfomance)
