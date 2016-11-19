# [Visual Studio Debugger Extensibility](visual-studio-debugger-extensibility.md)
# [Choosing a Debug Engine Implementation Strategy](choosing-a-debug-engine-implementation-strategy.md)
# [Visual Studio Debugging Samples](visual-studio-debugging-samples.md)
# [Creating a Custom Debug Engine](creating-a-custom-debug-engine.md)
## [Registering a Custom Debug Engine](registering-a-custom-debug-engine.md)
## [Enabling a Program to Be Debugged](enabling-a-program-to-be-debugged.md)
### [Getting a Port](getting-a-port.md)
### [Registering the Program](registering-the-program.md)
### [Attaching to the Program](attaching-to-the-program.md)
### [Launch-based Attachment](launch-based-attachment.md)
### [Sending the Required Events](sending-the-required-events.md)
## [Execution Control and State Evaluation](execution-control-and-state-evaluation.md)
### [Program Control](program-control.md)
### [Breakpoint-Related Methods](breakpoint-related-methods.md)
### [Call Stack Evaluation](call-stack-evaluation.md)
### [Expression Evaluation (Visual Studio Debugging SDK)](expression-evaluation-visual-studio-debugging-sdk.md)
### [Control Events](control-events.md)
## [Sending Events](sending-events.md)
### [Event Sources (Visual Studio SDK)](event-sources-visual-studio-sdk.md)
### [Supported Event Types](supported-event-types.md)
### [Event Descriptions](event-descriptions.md)
## [Termination and Detaching](termination-and-detaching.md)
## [Calling Debugger Events](calling-debugger-events.md)
### [Attaching and Detaching to a Program](attaching-and-detaching-to-a-program.md)
### [Launching the Debugger](launching-the-debugger.md)
### [Terminating a Program](terminating-a-program.md)
### [Creating a Breakpoint](creating-a-breakpoint.md)
### [When a Breakpoint Binds or Becomes Unbound](when-a-breakpoint-binds-or-becomes-unbound.md)
### [Breakpoint Errors](breakpoint-errors.md)
### [Hitting a Breakpoint](hitting-a-breakpoint.md)
### [Deleting a Breakpoint](deleting-a-breakpoint.md)
### [Entering Break Mode](entering-break-mode.md)
### [Stepping in Break Mode](stepping-in-break-mode.md)
### [Expression Evaluation in Break Mode](expression-evaluation-in-break-mode.md)
### [Exception Handling (Visual Studio SDK)](exception-handling-visual-studio-sdk.md)
## [How To: Debug a Custom Debug Engine](how-to-debug-a-custom-debug-engine.md)
# [Getting Started with Debugger Extensibility](getting-started-with-debugger-extensibility.md)
## [Roadmap for Extending the Debugger](roadmap-for-extending-the-debugger.md)
## [Debugger Components](debugger-components.md)
### [Debug Package](debug-package.md)
### [Process Debug Manager](process-debug-manager.md)
### [Session Debug Manager](session-debug-manager.md)
### [Debug Engine](debug-engine.md)
### [Operational Modes](operational-modes.md)
### [Expression Evaluator](expression-evaluator.md)
### [Symbol Provider](symbol-provider.md)
### [Type Visualizer and Custom Viewer](type-visualizer-and-custom-viewer.md)
## [Debugger Concepts](debugger-concepts.md)
### [Debug Session](debug-session.md)
### [Servers (Visual Studio SDK)](servers-visual-studio-sdk.md)
### [Port Suppliers](port-suppliers.md)
### [Ports](ports.md)
### [Processes](processes.md)
### [Program Nodes](program-nodes.md)
### [Programs](programs.md)
### [Threads](threads.md)
### [Stack Frames](stack-frames.md)
### [Modules](modules.md)
### [Breakpoints (Visual Studio SDK)](breakpoints-visual-studio-sdk.md)
## [Debugger Contexts](debugger-contexts.md)
### [Code Context](code-context.md)
### [Document Position](document-position.md)
### [Document Context](document-context.md)
### [Expression Evaluation Context](expression-evaluation-context.md)
## [Debugging Tasks](debugging-tasks.md)
### [Security Issues](security-issues.md)
### [Launching a Program](launching-a-program.md)
#### [Notifying the Port](notifying-the-port.md)
#### [Attaching After a Launch](attaching-after-a-launch.md)
### [Attaching Directly to a Program](attaching-directly-to-a-program.md)
### [Sending Startup Events After a Launch](sending-startup-events-after-a-launch.md)
### [Control of Execution](control-of-execution.md)
### [Binding Breakpoints](binding-breakpoints.md)
### [Evaluating Expressions](evaluating-expressions.md)
### [Visualizing and Viewing Data](visualizing-and-viewing-data.md)
# [Writing a Common Language Runtime Expression Evaluator](writing-a-common-language-runtime-expression-evaluator.md)
## [Common Language Runtime and Expression Evaluation](common-language-runtime-and-expression-evaluation.md)
## [Expression Evaluator Architecture](expression-evaluator-architecture.md)
### [Evaluation Context](evaluation-context.md)
### [Key Expression Evaluator Interfaces](key-expression-evaluator-interfaces.md)
## [Registering an Expression Evaluator](registering-an-expression-evaluator.md)
## [Implementing an Expression Evaluator](implementing-an-expression-evaluator.md)
### [Expression Evaluator Implementation Strategy](expression-evaluator-implementation-strategy.md)
## [Displaying Locals](displaying-locals.md)
### [Sample Implementation of Locals](sample-implementation-of-locals.md)
#### [Implementing GetMethodProperty](implementing-getmethodproperty.md)
#### [Enumerating Locals](enumerating-locals.md)
#### [Getting Local Properties](getting-local-properties.md)
#### [Getting Local Values](getting-local-values.md)
#### [Evaluating Locals](evaluating-locals.md)
## [Evaluating a Watch Window Expression](evaluating-a-watch-window-expression.md)
### [Sample Implementation of Expression Evaluation](sample-implementation-of-expression-evaluation.md)
### [Evaluating a Watch Expression](evaluating-a-watch-expression.md)
## [Changing the Value of a Local](changing-the-value-of-a-local.md)
### [Sample Implementation of Changing Values](sample-implementation-of-changing-values.md)
## [Implementing Type Visualizers and Custom Viewers](implementing-type-visualizers-and-custom-viewers.md)
# [Implementing a Port Supplier](implementing-a-port-supplier.md)
## [Implementing and Registering a Port Supplier](implementing-and-registering-a-port-supplier.md)
## [Required Port Supplier Interfaces](required-port-supplier-interfaces.md)
# [Parallel Extension Internals for the .NET Framework](parallel-extension-internals-for-the-dotnet-framework.md)
## [Task Class - Internal Members](task-class-internal-members.md)
### [m_action Field](m-action-field.md)
### [m_contingentProperties Field](m-contingentproperties-field.md)
### [m_parent Field](m-parent-field.md)
### [m_stateFlags Field](m-stateflags-field.md)
### [m_stateObject Field](m-stateobject-field.md)
### [m_taskId Field](m-taskid-field.md)
### [s_taskIdCounter Field](s-taskidcounter-field.md)
### [TASK_STATE_CANCELED Field](task-state-canceled-field.md)
### [TASK_STATE_EXECUTED Field](task-state-executed-field.md)
### [TASK_STATE_FAULTED Field](task-state-faulted-field.md)
### [TASK_STATE_RAN_TO_COMPLETION Field](task-state-ran-to-completion-field.md)
### [TASK_STATE_WAITING_ON_CHILDREN Field](task-state-waiting-on-children-field.md)
### [SetNotificationForWaitCompletion Method](setnotificationforwaitcompletion-method.md)
### [NotifyDebuggerOfWaitCompletion Method](notifydebuggerofwaitcompletion-method.md)
## [TaskScheduler Class - Internal Members](taskscheduler-class-internal-members.md)
### [GetScheduledTasksForDebugger Method](getscheduledtasksfordebugger-method.md)
### [GetTaskSchedulersForDebugger Method](gettaskschedulersfordebugger-method.md)
## [ContingentProperties Class - Internal Members](contingentproperties-class-internal-members.md)
### [m_children Field](m-children-field.md)
## [AsyncTaskMethodBuilder Structure - Internal Members](asynctaskmethodbuilder-structure-internal-members.md)
### [AsyncTaskMethodBuilder.ObjectIdForDebugger Property](asynctaskmethodbuilder-objectidfordebugger-property.md)
### [AsyncTaskMethodBuilder.m_builder Field](asynctaskmethodbuilder-m-builder-field.md)
## [AsyncTaskMethodBuilder<TResult> Structure - Internal Members](asynctaskmethodbuilder-tresult-structure-internal-members.md)
### [AsyncTaskMethodBuilder<TResult>.ObjectIdForDebugger Property](asynctaskmethodbuilder-tresult-objectidfordebugger-property.md)
### [AsyncTaskMethodBuilder<TResult>.m_task Field](asynctaskmethodbuilder-tresult-m-task-field.md)
## [AsyncVoidMethodBuilder Structure - Internal Members](asyncvoidmethodbuilder-structure-internal-members.md)
### [AsyncVoidMethodBuilder.ObjectIdForDebugger Property](asyncvoidmethodbuilder-objectidfordebugger-property.md)
### [AsyncVoidMethodBuilder.m_objectIdForDebugger Field](asyncvoidmethodbuilder-m-objectidfordebugger-field.md)