# SPDX-License-Identifier: GPL-2.0-only

obj-$(CONFIG_SECURITY_LKRG) := p_lkrg.o
p_lkrg-objs += modules/ksyms/p_resolve_ksym.o \
                  modules/hashing/p_lkrg_fast_hash.o \
                  modules/comm_channel/p_comm_channel.o \
                  modules/integrity_timer/p_integrity_timer.o \
                  modules/kmod/p_kmod.o \
                  modules/database/CPU.o \
                  modules/database/arch/x86/p_x86_metadata.o \
                  modules/database/arch/x86/p_switch_idt/p_switch_idt.o \
                  modules/database/arch/arm64/p_arm64_metadata.o \
                  modules/database/arch/arm/p_arm_metadata.o \
                  modules/database/arch/p_arch_metadata.o \
                  modules/database/JUMP_LABEL/p_arch_jump_label_transform/p_arch_jump_label_transform.o \
                  modules/database/JUMP_LABEL/p_arch_jump_label_transform_apply/p_arch_jump_label_transform_apply.o \
                  modules/database/FTRACE/p_ftrace_modify_all_code/p_ftrace_modify_all_code.o \
                  modules/database/FTRACE/p_ftrace_enable_sysctl/p_ftrace_enable_sysctl.o \
                  modules/database/p_database.o \
                  modules/notifiers/p_notifiers.o \
                  modules/self-defense/hiding/p_hiding.o \
                  modules/exploit_detection/p_rb_ed_trees/p_rb_ed_pids/p_rb_ed_pids_tree.o \
                  modules/exploit_detection/syscalls/p_install.o \
                  modules/exploit_detection/syscalls/exec/p_security_bprm_committing_creds/p_security_bprm_committing_creds.o \
                  modules/exploit_detection/syscalls/exec/p_security_bprm_committed_creds/p_security_bprm_committed_creds.o \
                  modules/exploit_detection/syscalls/p_call_usermodehelper/p_call_usermodehelper.o \
                  modules/exploit_detection/syscalls/p_call_usermodehelper_exec/p_call_usermodehelper_exec.o \
                  modules/exploit_detection/syscalls/p_do_exit/p_do_exit.o \
                  modules/exploit_detection/syscalls/p_wake_up_new_task/p_wake_up_new_task.o \
                  modules/exploit_detection/syscalls/p_sys_setuid/p_sys_setuid.o \
                  modules/exploit_detection/syscalls/p_sys_setreuid/p_sys_setreuid.o \
                  modules/exploit_detection/syscalls/p_sys_setresuid/p_sys_setresuid.o \
                  modules/exploit_detection/syscalls/p_sys_setfsuid/p_sys_setfsuid.o \
                  modules/exploit_detection/syscalls/p_sys_setgid/p_sys_setgid.o \
                  modules/exploit_detection/syscalls/p_sys_setregid/p_sys_setregid.o \
                  modules/exploit_detection/syscalls/p_sys_setresgid/p_sys_setresgid.o \
                  modules/exploit_detection/syscalls/p_sys_setfsgid/p_sys_setfsgid.o \
                  modules/exploit_detection/syscalls/p_set_current_groups/p_set_current_groups.o \
                  modules/exploit_detection/syscalls/p_generic_permission/p_generic_permission.o \
                  modules/exploit_detection/syscalls/p_sel_write_enforce/p_sel_write_enforce.o \
                  modules/exploit_detection/syscalls/p_seccomp/p_seccomp.o \
                  modules/exploit_detection/syscalls/p_sys_unshare/p_sys_unshare.o \
                  modules/exploit_detection/syscalls/p_sys_setns/p_sys_setns.o \
                  modules/exploit_detection/syscalls/caps/p_sys_capset/p_sys_capset.o \
                  modules/exploit_detection/syscalls/caps/p_cap_task_prctl/p_cap_task_prctl.o \
                  modules/exploit_detection/syscalls/keyring/p_key_change_session_keyring/p_key_change_session_keyring.o \
                  modules/exploit_detection/syscalls/keyring/p_sys_add_key/p_sys_add_key.o \
                  modules/exploit_detection/syscalls/keyring/p_sys_request_key/p_sys_request_key.o \
                  modules/exploit_detection/syscalls/keyring/p_sys_keyctl/p_sys_keyctl.o \
                  modules/exploit_detection/syscalls/p_security_ptrace_access/p_security_ptrace_access.o \
                  modules/exploit_detection/syscalls/compat/p_compat_sys_keyctl/p_compat_sys_keyctl.o \
                  modules/exploit_detection/syscalls/compat/p_compat_sys_capset/p_compat_sys_capset.o \
                  modules/exploit_detection/syscalls/compat/p_compat_sys_add_key/p_compat_sys_add_key.o \
                  modules/exploit_detection/syscalls/compat/p_compat_sys_request_key/p_compat_sys_request_key.o \
                  modules/exploit_detection/syscalls/__x32/p_x32_sys_keyctl/p_x32_sys_keyctl.o \
                  modules/exploit_detection/syscalls/override/p_override_creds/p_override_creds.o \
                  modules/exploit_detection/syscalls/override/p_revert_creds/p_revert_creds.o \
                  modules/exploit_detection/syscalls/override/overlayfs/p_ovl_create_or_link/p_ovl_create_or_link.o \
                  modules/exploit_detection/syscalls/pCFI/p_mark_inode_dirty/p_mark_inode_dirty.o \
                  modules/exploit_detection/syscalls/pCFI/p_schedule/p_schedule.o \
                  modules/exploit_detection/syscalls/pCFI/p___queue_work/p___queue_work.o \
                  modules/exploit_detection/syscalls/pCFI/p_lookup_fast/p_lookup_fast.o \
                  modules/exploit_detection/syscalls/p_capable/p_capable.o \
                  modules/exploit_detection/syscalls/p_scm_send/p_scm_send.o \
                  modules/exploit_detection/p_exploit_detection.o \
                  p_lkrg_main.o
 
