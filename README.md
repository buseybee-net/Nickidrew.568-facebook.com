# Nickidrew.568-facebook.com
URL-Track
 $ go test -run "TestState" -v
=== RUN   TestState
--- PASS: TestState (0.00s)
=== RUN   TestStateDeepCopyObject
--- PASS: TestStateDeepCopyObject (0.00s)
=== RUN   TestStateDeepCopy
--- PASS: TestStateDeepCopy (0.00s)
=== RUN   TestStateHasResourceInstanceObjects
=== RUN   TestStateHasResourceInstanceObjects/empty
=== RUN   TestStateHasResourceInstanceObjects/one_current,_ready_object_in_root_module
=== RUN   TestStateHasResourceInstanceObjects/one_current,_ready_object_in_child_module
=== RUN   TestStateHasResourceInstanceObjects/one_current,_tainted_object_in_root_module
=== RUN   TestStateHasResourceInstanceObjects/one_deposed,_ready_object_in_root_module
=== RUN   TestStateHasResourceInstanceObjects/one_empty_resource_husk_in_root_module
=== RUN   TestStateHasResourceInstanceObjects/one_current_data_resource_object_in_root_module
--- PASS: TestStateHasResourceInstanceObjects (0.00s)
    --- PASS: TestStateHasResourceInstanceObjects/empty (0.00s)
    --- PASS: TestStateHasResourceInstanceObjects/one_current,_ready_object_in_root_module (0.00s)
    --- PASS: TestStateHasResourceInstanceObjects/one_current,_ready_object_in_child_module (0.00s)
    --- PASS: TestStateHasResourceInstanceObjects/one_current,_tainted_object_in_root_module (0.00s)
    --- PASS: TestStateHasResourceInstanceObjects/one_deposed,_ready_object_in_root_module (0.00s)
    --- PASS: TestStateHasResourceInstanceObjects/one_empty_resource_husk_in_root_module (0.00s)
    --- PASS: TestStateHasResourceInstanceObjects/one_current_data_resource_object_in_root_module (0.00s)
=== RUN   TestStateHasRootOutputValues
=== RUN   TestStateHasRootOutputValues/empty
=== RUN   TestStateHasRootOutputValues/one_output_value
=== RUN   TestStateHasRootOutputValues/one_secret_output_value
=== RUN   TestStateHasRootOutputValues/one_output_value_in_child_module
=== RUN   TestStateHasRootOutputValues/one_output_value_in_multi_module
--- PASS: TestStateHasRootOutputValues (0.00s)
    --- PASS: TestStateHasRootOutputValues/empty (0.00s)
    --- PASS: TestStateHasRootOutputValues/one_output_value (0.00s)
    --- PASS: TestStateHasRootOutputValues/one_secret_output_value (0.00s)
    --- PASS: TestStateHasRootOutputValues/one_output_value_in_child_module (0.00s)
    --- PASS: TestStateHasRootOutputValues/one_output_value_in_multi_module (0.00s)
=== RUN   TestState_MoveAbsResource
=== RUN   TestState_MoveAbsResource/basic_move
=== RUN   TestState_MoveAbsResource/move_to_new_module
=== RUN   TestState_MoveAbsResource/from_a_child_module_to_root
=== RUN   TestState_MoveAbsResource/module_to_new_module
=== RUN   TestState_MoveAbsResource/module_to_new_module#01
--- PASS: TestState_MoveAbsResource (0.00s)
    --- PASS: TestState_MoveAbsResource/basic_move (0.00s)
    --- PASS: TestState_MoveAbsResource/move_to_new_module (0.00s)
    --- PASS: TestState_MoveAbsResource/from_a_child_module_to_root (0.00s)
    --- PASS: TestState_MoveAbsResource/module_to_new_module (0.00s)
    --- PASS: TestState_MoveAbsResource/module_to_new_module#01 (0.00s)
=== RUN   TestState_MaybeMoveAbsResource
=== RUN   TestState_MaybeMoveAbsResource/first_move
=== RUN   TestState_MaybeMoveAbsResource/noop
--- PASS: TestState_MaybeMoveAbsResource (0.00s)
    --- PASS: TestState_MaybeMoveAbsResource/first_move (0.00s)
    --- PASS: TestState_MaybeMoveAbsResource/noop (0.00s)
=== RUN   TestState_MoveAbsResourceInstance
=== RUN   TestState_MoveAbsResourceInstance/resource_to_resource_instance
=== RUN   TestState_MoveAbsResourceInstance/move_to_new_module
--- PASS: TestState_MoveAbsResourceInstance (0.00s)
    --- PASS: TestState_MoveAbsResourceInstance/resource_to_resource_instance (0.00s)
    --- PASS: TestState_MoveAbsResourceInstance/move_to_new_module (0.00s)
=== RUN   TestState_MaybeMoveAbsResourceInstance
=== RUN   TestState_MaybeMoveAbsResourceInstance/first_move
=== RUN   TestState_MaybeMoveAbsResourceInstance/noop
--- PASS: TestState_MaybeMoveAbsResourceInstance (0.00s)
    --- PASS: TestState_MaybeMoveAbsResourceInstance/first_move (0.00s)
    --- PASS: TestState_MaybeMoveAbsResourceInstance/noop (0.00s)
=== RUN   TestState_MoveModuleInstance
--- PASS: TestState_MoveModuleInstance (0.00s)
=== RUN   TestState_MaybeMoveModuleInstance
=== RUN   TestState_MaybeMoveModuleInstance/first_move
=== RUN   TestState_MaybeMoveModuleInstance/noop
--- PASS: TestState_MaybeMoveModuleInstance (0.00s)
    --- PASS: TestState_MaybeMoveModuleInstance/first_move (0.00s)
    --- PASS: TestState_MaybeMoveModuleInstance/noop (0.00s)
=== RUN   TestState_MoveModule
=== RUN   TestState_MoveModule/basic
=== RUN   TestState_MoveModule/nested_modules
--- PASS: TestState_MoveModule (0.00s)
    --- PASS: TestState_MoveModule/basic (0.00s)
    --- PASS: TestState_MoveModule/nested_modules (0.00s)
PASS
ok      github.com/hashicorp/terraform/internal/states  0.298s
