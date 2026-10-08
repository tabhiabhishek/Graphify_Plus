# Knowledge Graph Report: Projects

**Project:** Projects  
**Path:** D:\Projects  
**Nodes:** 75667 | **Edges:** 193026 | **Communities:** 18  
**Version:** 30

## Node Types

- **import**: 31893
- **method**: 24887
- **function**: 9092
- **class**: 6208
- **module**: 3088
- **rationale**: 499

## God Nodes (architectural hubs)

### __init__ (module) — 219 connections
File: `venv311\Lib\site-packages\igraph\__init__.py` | Community: -1
Connects to: networkx.algorithms.approximation (import), networkx.algorithms.assortativity (import), networkx.algorithms.assortativity.* (import), networkx.algorithms.asteroidal.* (import), networkx.algorithms.bipartite (import), networkx.algorithms.bipartite.complete_bipartite_graph (import), networkx.algorithms.bipartite.is_bipartite (import), networkx.algorithms.bipartite.projected_graph (import), networkx.algorithms.boundary.* (import), networkx.algorithms.bridges.* (import)

### core_schema (module) — 188 connections
File: `venv311\Lib\site-packages\pydantic_core\core_schema.py` | Community: -1
Connects to: AfterValidatorFunctionSchema (class), AnySchema (class), ArgumentsParameter (class), ArgumentsSchema (class), ArgumentsV3Parameter (class), ArgumentsV3Schema (class), BeforeValidatorFunctionSchema (class), BoolSchema (class), BytesSchema (class), CallSchema (class)

### _generate_schema (module) — 184 connections
File: `venv311\Lib\site-packages\pydantic\_internal\_generate_schema.py` | Community: -1
Connects to: GenerateSchema (class), InvalidSchemaError (class), [HACK] we don't want to emit the warning for `FieldInfo` subclasses, because FastAPI do (rationale), [NOTE] This conditional can be removed when we drop support for Python 3.10. (rationale), [NOTE] This does not play very well with type checkers. For example, (rationale), [NOTE] if schema is of type `'definition-ref'`, we might want to copy it as a (rationale), [NOTE] subtle difference: `tuple[()]` gives `params=()`, whereas `typing.Tuple[()]` giv (rationale), [NOTE] this logic doesn't play well when core schemas with deferred discriminator metad (rationale), [NOTE] this must come before the `is_namedtuple()` check as enums values (rationale), [TODO] Should we support exclude_if from annotations? (rationale)

### types (module) — 170 connections
File: `venv311\Lib\site-packages\mcp\types.py` | Community: -1
Connects to: Annotations (class), AudioContent (class), BaseMetadata (class), BlobResourceContents (class), CallToolRequest (class), CallToolRequestParams (class), CallToolResult (class), CancelTaskRequest (class), CancelTaskRequestParams (class), CancelTaskResult (class)

### more (module) — 151 connections
File: `venv311\Lib\site-packages\pkg_resources\_vendor\more_itertools\more.py` | Community: -1
Connects to: AbortThread (class), SequenceView (class), UnequalIterablesError (class), _islice_helper (function), _sample_unweighted (function), _sample_weighted (function), _zip_equal_generator (function), adjacent (function), all_unique (function), always_iterable (function)

### __init__ (module) — 143 connections
File: `venv311\Lib\site-packages\pkg_resources\__init__.py` | Community: -1
Connects to: networkx.algorithms.approximation (import), networkx.algorithms.assortativity (import), networkx.algorithms.assortativity.* (import), networkx.algorithms.asteroidal.* (import), networkx.algorithms.bipartite (import), networkx.algorithms.bipartite.complete_bipartite_graph (import), networkx.algorithms.bipartite.is_bipartite (import), networkx.algorithms.bipartite.projected_graph (import), networkx.algorithms.boundary.* (import), networkx.algorithms.bridges.* (import)

### __init__ (module) — 142 connections
File: `venv311\Lib\site-packages\pip\_vendor\pkg_resources\__init__.py` | Community: -1
Connects to: networkx.algorithms.approximation (import), networkx.algorithms.assortativity (import), networkx.algorithms.assortativity.* (import), networkx.algorithms.asteroidal.* (import), networkx.algorithms.bipartite (import), networkx.algorithms.bipartite.complete_bipartite_graph (import), networkx.algorithms.bipartite.is_bipartite (import), networkx.algorithms.bipartite.projected_graph (import), networkx.algorithms.boundary.* (import), networkx.algorithms.bridges.* (import)

### _asyncio (module) — 141 connections
File: `venv311\Lib\site-packages\anyio\_backends\_asyncio.py` | Community: -1
Connects to: AsyncIOBackend (class), AsyncIOTaskInfo (class), CancelScope (class), CapacityLimiter (class), CapacityLimiterStatistics (import), ConnectedUDPSocket (class), ConnectedUNIXDatagramSocket (class), DatagramProtocol (class), Event (class), EventStatistics (import)

### more (module) — 135 connections
File: `venv311\Lib\site-packages\setuptools\_vendor\more_itertools\more.py` | Community: -1
Connects to: AbortThread (class), SequenceView (class), UnequalIterablesError (class), _islice_helper (function), _sample_unweighted (function), _sample_weighted (function), _zip_equal_generator (function), adjacent (function), all_unique (function), always_iterable (function)

### __init__ (module) — 128 connections
File: `venv311\Lib\site-packages\networkx\algorithms\__init__.py` | Community: -1
Connects to: networkx.algorithms.approximation (import), networkx.algorithms.assortativity (import), networkx.algorithms.assortativity.* (import), networkx.algorithms.asteroidal.* (import), networkx.algorithms.bipartite (import), networkx.algorithms.bipartite.complete_bipartite_graph (import), networkx.algorithms.bipartite.is_bipartite (import), networkx.algorithms.bipartite.projected_graph (import), networkx.algorithms.boundary.* (import), networkx.algorithms.bridges.* (import)

### core (module) — 121 connections
File: `venv311\Lib\site-packages\pip\_vendor\pyparsing\core.py` | Community: -1

### validators (module) — 121 connections
File: `venv311\Lib\site-packages\pydantic\v1\validators.py` | Community: -1

### CParser (class) — 119 connections
File: `venv311\Lib\site-packages\pycparser\c_parser.py` | Community: -1

### schema (module) — 116 connections
File: `venv311\Lib\site-packages\pydantic\v1\schema.py` | Community: -1

### core (module) — 114 connections
File: `venv311\Lib\site-packages\pkg_resources\_vendor\pyparsing\core.py` | Community: -1

## Communities (clusters)

## File Map

**app.js** — function: addLogEntry, addProject, addProjectToWorkspace, buildProject, checkCoworkStatus, closeExplorer; module: app
**vis-network.min.js** — module: vis-network.min
**__init__.py** — module: __init__
**cli.py** — function: build, find_path, main, plugin, plugin_install, plugin_uninstall; 24 imports; module: cli
**db.py** — class: Community, CrossProjectEdge, Edge, GraphDB, Node, Project; 15 imports; method: GraphDB.__init__, GraphDB._connect, GraphDB._init_db, GraphDB._row_to_cross_edge, GraphDB._row_to_node, GraphDB._upgrade_schema; module: db
**diff.py** — class: DiffImpact; function: analyze_diff_impact, format_diff_report, get_changed_files, incremental_update; 9 imports; module: diff
**__init__.py** — module: __init__
**ast_extract.py** — function: _extract_python_ast, _extract_with_regex, _extract_with_treesitter, _get_call_name, _make_id, _make_relative; 10 imports; module: ast_extract; rationale: [WHY] , # HACK:, # NOTE:, # IMPORTANT:, # TODO:)
**graph.py** — function: _run_leiden_clustering, build_graph, find_surprising_connections, generate_report; 11 imports; module: graph
**mcp_entry.py** — function: main; 5 imports; module: mcp_entry
**mcp_server.py** — function: _dispatch, _handle_diff_impact, _handle_get_cross_edges, _handle_list_workspaces, _handle_rebuild, _handle_semantic_enrich; 22 imports; module: mcp_server
**plugin_installer.py** — function: install_claude_code, install_generic, install_plugin, uninstall_claude_code; 4 imports; module: plugin_installer
**report_generator.py** — function: _update_claude_md, generate_rich_report; 5 imports; module: report_generator
**semantic_extract.py** — function: _build_prompt, _call_claude_api, _call_llm, _call_ollama, _guess_language, _parse_response; 8 imports; module: semantic_extract
**server.py** — function: create_app, run_server; 34 imports; module: server
**watcher.py** — class: FileWatcher; 15 imports; method: FileWatcher.__init__, FileWatcher._on_file_change, FileWatcher._process_changes, FileWatcher.stop_all, FileWatcher.stop_watching, FileWatcher.watch_project; module: watcher
**workspace.py** — class: CrossImpactResult; function: _cosine_similarity, _get_already_linked_node_ids, _get_linkable_nodes, _normalize_label, enrich_workspace, format_cross_impact_report; 17 imports; module: workspace
**test_e2e.py** — 8 imports; module: test_e2e
**__init__.py** — class: DistutilsMetaFinder, _TrivialRe, shim; function: add_shim, clear_distutils, do_override, enabled, ensure_local_distutils, insert_shim; 7 imports; method: DistutilsMetaFinder.find_spec, DistutilsMetaFinder.frame_file_is_setup, DistutilsMetaFinder.is_cpython, DistutilsMetaFinder.pip_imported_during_build, DistutilsMetaFinder.spec_for_distutils, DistutilsMetaFinder.spec_for_pip; module: __init__
**override.py** — module: override
**__init__.py** — function: Binary, Date, DateFromTicks, Time, TimeFromTicks, Timestamp; 25 imports; module: __init__
**ado_consts.py** — function: ado_direction_name, ado_type_name; module: ado_consts; rationale: [TODO] Update to https://learn.microsoft.com/en-us/sql/ado/reference/ado-api/ado-enumer, [TODO] Update to https://learn.microsoft.com/en-us/sql/ado/reference/ado-api/datatypeen
**adodbapi.py** — class: Connection, Cursor; function: _configure_parameter, connect, format_parameters, getIndexedValue, make_COM_connecter; 13 imports; method: Connection.__del__, Connection.__enter__, Connection.__exit__, Connection.__getattr__, Connection.__init__, Connection.__setattr__; module: adodbapi; rationale: [NOTE] ADO does not preserve the parameter list, even if "Prepared" is True, so we must, [TODO] Is this the correct definition according to the DB API 2 Spec ?
**apibase.py** — class: DBAPITypeObject, DataError, DatabaseError, Error, FetchFailedError, IntegrityError; function: _convertNumberWithCulture, changeFormatToQmark, changeNamedToQmark, convert_to_python, cvtBuffer, cvtDecimal; 11 imports; method: DBAPITypeObject.__eq__, DBAPITypeObject.__init__, DBAPITypeObject.__ne__, MultiMap.__init__, MultiMap.__setitem__, SQLrow.__getattr__; module: apibase; rationale: [NOTE] Usage of Unix ticks for database interfacing can cause troubles because of the l
**db_print.py** — 3 imports; module: db_print
**db_table_names.py** — 2 imports; module: db_table_names
**xls_read.py** — 3 imports; module: xls_read
**xls_write.py** — 3 imports; module: xls_write
**is64bit.py** — function: Python, os; 3 imports; module: is64bit
**process_connect_string.py** — function: macro_call, process; 5 imports; module: process_connect_string
**schema_table.py** — function: names; 1 imports; module: schema_table
**setup.py** — function: setup_package; 2 imports; module: setup
**adodbapitest.py** — class: CommonDBTests, TestADOwithAccessDB, TestADOwithMySql, TestADOwithPostgres, TestADOwithSQLServer, TestPythonDateTimeConverter; function: randomstring; 11 imports; method: CommonDBTests.getConnection, CommonDBTests.getCursor, CommonDBTests.getEngine, CommonDBTests.helpCreateAndPopulateTableTemp, CommonDBTests.helpForceDropOnTblTemp, CommonDBTests.helpRollbackTblTemp; module: adodbapitest; rationale: [NOTE] building the test table without using parameter substitution, [NOTE] this poor SQL code, but a valid test
**adodbapitestconfig.py** — 7 imports; module: adodbapitestconfig
**dbapi20.py** — class: DatabaseAPI20Test; 2 imports; method: DatabaseAPI20Test._connect, DatabaseAPI20Test._paraminsert, DatabaseAPI20Test._populate, DatabaseAPI20Test.executeDDL1, DatabaseAPI20Test.executeDDL2, DatabaseAPI20Test.help_nextset_setUp; module: dbapi20
**is64bit.py** — function: Python, os; 3 imports; module: is64bit
**setuptestframework.py** — function: _cleanup_function, find_ado_path, getcleanupfunction, makeadopackage, makemdb, maketemp; 5 imports; module: setuptestframework
**test_adodbapi_dbapi20.py** — class: test_adodbapi; 7 imports; method: test_adodbapi.__init__, test_adodbapi.getTestMethodName, test_adodbapi.help_nextset_setUp, test_adodbapi.help_nextset_tearDown, test_adodbapi.setUp, test_adodbapi.tearDown; module: test_adodbapi_dbapi20
**tryconnection.py** — function: try_connection, try_operation_with_expected_exception; 1 imports; module: tryconnection
**__init__.py** — 1 imports; module: __init__
**main.py** — class: Doc; method: Doc.__eq__, Doc.__hash__, Doc.__init__, Doc.__repr__; module: main
**__init__.py** — class: BaseMetadata, Ge, GroupedMetadata, Gt, Interval, Le; 25 imports; method: GroupedMetadata.__is_annotated_types_grouped_metadata__, GroupedMetadata.__iter__, Interval.__iter__, Len.__iter__, Not.__call__, Predicate.__repr__; module: __init__
**test_cases.py** — class: Case; function: cases; 18 imports; module: test_cases
**__init__.py** — function: __getattr__; 88 imports; module: __init__
**_asyncio.py** — class: AsyncIOBackend, AsyncIOTaskInfo, CancelScope, CapacityLimiter, ConnectedUDPSocket, ConnectedUNIXDatagramSocket; function: _forcibly_shutdown_process_pool_on_exit, _shutdown_process_pool_on_exit, _task_started, find_root_task, is_anyio_cancellation; 109 imports; method: AsyncIOBackend.cancel_shielded_checkpoint, AsyncIOBackend.cancelled_exception_class, AsyncIOBackend.check_cancelled, AsyncIOBackend.checkpoint, AsyncIOBackend.checkpoint_if_cancelled, AsyncIOBackend.connect_tcp; module: _asyncio
**_trio.py** — class: CancelScope, CapacityLimiter, ConnectedUDPSocket, ConnectedUNIXDatagramSocket, Event, Lock; function: _shutdown_process_pool, ensure_returns_coro; 88 imports; method: CancelScope.__enter__, CancelScope.__exit__, CancelScope.__init__, CancelScope.__new__, CancelScope.cancel, CancelScope.cancel_called; module: _trio
**_asyncio_selector_thread.py** — class: Selector; function: get_selector; 11 imports; method: Selector.__init__, Selector._notify_self, Selector._stop, Selector.add_reader, Selector.add_writer, Selector.remove_reader; module: _asyncio_selector_thread
**_contextmanagers.py** — class: AsyncContextManagerMixin, ContextManagerMixin, _SupportsAsyncCtxMgr, _SupportsCtxMgr; 12 imports; method: AsyncContextManagerMixin.__aenter__, AsyncContextManagerMixin.__aexit__, AsyncContextManagerMixin.__asynccontextmanager__, ContextManagerMixin.__contextmanager__, ContextManagerMixin.__enter__, ContextManagerMixin.__exit__; module: _contextmanagers
**_eventloop.py** — function: claim_worker_thread, current_async_library, current_time, get_all_backends, get_async_backend, get_available_backends; 22 imports; module: _eventloop
**_exceptions.py** — class: BrokenResourceError, BrokenWorkerInterpreter, BrokenWorkerProcess, BusyResourceError, ClosedResourceError, ConnectionFailed; function: iterate_exceptions; 6 imports; method: BrokenWorkerInterpreter.__init__, BrokenWorkerInterpreter.__str__, BusyResourceError.__init__, DelimiterNotFound.__init__, IncompleteRead.__init__, RunFinishedError.__init__; module: _exceptions
**_fileio.py** — class: AsyncFile, Path, _PathIterator; function: open_file, wrap_file; 32 imports; method: AsyncFile.__aiter__, AsyncFile.__getattr__, AsyncFile.__init__, AsyncFile.aclose, AsyncFile.flush, AsyncFile.limiter; module: _fileio
**_resources.py** — function: aclose_forcefully; 3 imports; module: _resources
**_signals.py** — function: open_signal_receiver; 5 imports; module: _signals
**_sockets.py** — class: TCPConnectable, UNIXConnectable; function: as_connectable, connect_tcp, connect_unix, convert_ipv6_sockaddr, create_connected_udp_socket, create_connected_unix_datagram_socket; 48 imports; method: TCPConnectable.__post_init__, TCPConnectable.connect, UNIXConnectable.connect; module: _sockets
**_streams.py** — class: create_memory_object_stream; 7 imports; method: create_memory_object_stream.__new__; module: _streams
**_subprocesses.py** — function: open_process, run_process; 17 imports; module: _subprocesses
**_synchronization.py** — class: CapacityLimiter, CapacityLimiterAdapter, CapacityLimiterStatistics, Condition, ConditionStatistics, Event; 14 imports; method: CapacityLimiter.__aenter__, CapacityLimiter.__aexit__, CapacityLimiter.__new__, CapacityLimiter.acquire, CapacityLimiter.acquire_nowait, CapacityLimiter.acquire_on_behalf_of; module: _synchronization
**_tasks.py** — class: CancelScope, TaskHandle, _IgnoredTaskStatus; function: create_task_group, current_effective_deadline, fail_after, move_on_after; 28 imports; method: CancelScope.__enter__, CancelScope.__exit__, CancelScope.__new__, CancelScope.cancel, CancelScope.cancel_called, CancelScope.cancelled_caught; module: _tasks
**_tempfile.py** — class: NamedTemporaryFile, SpooledTemporaryFile, TemporaryDirectory, TemporaryFile; function: gettempdir, gettempdirb, mkdtemp, mkstemp; 20 imports; method: NamedTemporaryFile.__aenter__, NamedTemporaryFile.__aexit__, NamedTemporaryFile.__init__, SpooledTemporaryFile.__init__, SpooledTemporaryFile._check, SpooledTemporaryFile.aclose; module: _tempfile
**_testing.py** — class: TaskInfo; function: get_current_task, get_running_tasks, wait_all_tasks_blocked; 6 imports; method: TaskInfo.__eq__, TaskInfo.__hash__, TaskInfo.__init__, TaskInfo.__repr__, TaskInfo.has_pending_cancellation; module: _testing
**_typedattr.py** — class: TypedAttributeProvider, TypedAttributeSet; function: typed_attribute; 8 imports; method: TypedAttributeProvider.extra, TypedAttributeProvider.extra_attributes, TypedAttributeSet.__init_subclass__; module: _typedattr
**__init__.py** — 45 imports; module: __init__
**_eventloop.py** — class: AsyncBackend; 44 imports; method: AsyncBackend.cancel_shielded_checkpoint, AsyncBackend.cancelled_exception_class, AsyncBackend.check_cancelled, AsyncBackend.checkpoint, AsyncBackend.checkpoint_if_cancelled, AsyncBackend.connect_tcp; module: _eventloop
**_resources.py** — class: AsyncResource; 5 imports; method: AsyncResource.__aenter__, AsyncResource.__aexit__, AsyncResource.aclose; module: _resources
**_sockets.py** — class: ConnectedUDPSocket, ConnectedUNIXDatagramSocket, SocketAttribute, SocketListener, SocketStream, UDPSocket; function: _validate_socket; 25 imports; method: ConnectedUDPSocket.from_socket, ConnectedUNIXDatagramSocket.from_socket, SocketListener.accept, SocketListener.from_socket, SocketListener.serve, SocketStream.from_socket; module: _sockets
**_streams.py** — class: ByteReceiveStream, ByteSendStream, ByteStream, ByteStreamConnectable, Listener, ObjectReceiveStream; 12 imports; method: ByteReceiveStream.__aiter__, ByteReceiveStream.__anext__, ByteReceiveStream.receive, ByteSendStream.send, ByteStream.send_eof, ByteStreamConnectable.connect; module: _streams
**_subprocesses.py** — class: Process; 6 imports; method: Process.kill, Process.pid, Process.returncode, Process.send_signal, Process.stderr, Process.stdin; module: _subprocesses
**_tasks.py** — class: TaskGroup, TaskStatus; function: call_for_coroutine, get_callable_name; 22 imports; method: TaskGroup.__aenter__, TaskGroup.__aexit__, TaskGroup.cancel, TaskGroup.create_task, TaskGroup.start, TaskGroup.start_soon; module: _tasks
**_testing.py** — class: TestRunner; 10 imports; method: TestRunner.__enter__, TestRunner.__exit__, TestRunner.is_running, TestRunner.run_asyncgen_fixture, TestRunner.run_fixture, TestRunner.run_test; module: _testing
**from_thread.py** — class: BlockingPortal, BlockingPortalProvider, _BlockingAsyncContextManager, _BlockingPortalTaskStatus; function: _token_or_error, check_cancelled, run, run_sync, start_blocking_portal; 38 imports; method: BlockingPortal.__aenter__, BlockingPortal.__aexit__, BlockingPortal.__init__, BlockingPortal._call_func, BlockingPortal._check_running, BlockingPortal._spawn_task_from_thread; module: from_thread
**functools.py** — class: AsyncCacheInfo, AsyncCacheParameters, AsyncLRUCacheWrapper, _InitialMissingType, _LRUCacheWrapper, _LRUMethodWrapper; function: cache, lru_cache, reduce; 25 imports; method: AsyncLRUCacheWrapper.__call__, AsyncLRUCacheWrapper.__get__, AsyncLRUCacheWrapper.__init__, AsyncLRUCacheWrapper.cache_clear, AsyncLRUCacheWrapper.cache_info, AsyncLRUCacheWrapper.cache_parameters; module: functools
**itertools.py** — class: Chain, _IterableAsyncIterator, _TeeAsyncIterator, _TeeLink, _TeeState; function: _iterate, _operator_add, accumulate, batched, combinations, combinations_with_replacement; 23 imports; method: Chain.__call__, Chain.from_iterable, _IterableAsyncIterator.__anext__, _TeeAsyncIterator.__anext__, _TeeAsyncIterator.__init__, _TeeState.fill; module: itertools
**lowlevel.py** — class: EventLoopToken, RunVar, RunvarToken, _NoValueSet; function: cancel_shielded_checkpoint, checkpoint, checkpoint_if_cancelled, current_token; 13 imports; method: RunVar.__init__, RunVar.__repr__, RunVar._current_vars, RunVar.get, RunVar.reset, RunVar.set; module: lowlevel
**pytest_plugin.py** — class: FreePortFactory; function: anyio_backend, anyio_backend_name, anyio_backend_options, extract_backend_and_options, free_tcp_port, free_tcp_port_factory; 28 imports; method: FreePortFactory.__call__, FreePortFactory.__init__, FreePortFactory.kind; module: pytest_plugin
**buffered.py** — class: BufferedByteReceiveStream, BufferedByteStream, BufferedConnectable; 21 imports; method: BufferedByteReceiveStream.aclose, BufferedByteReceiveStream.buffer, BufferedByteReceiveStream.extra_attributes, BufferedByteReceiveStream.feed_data, BufferedByteReceiveStream.receive, BufferedByteReceiveStream.receive_exactly; module: buffered
**file.py** — class: FileReadStream, FileStreamAttribute, FileWriteStream, _BaseFileStream; 17 imports; method: FileReadStream.from_path, FileReadStream.receive, FileReadStream.seek, FileReadStream.tell, FileWriteStream.from_path, FileWriteStream.send; module: file
**memory.py** — class: MemoryObjectReceiveStream, MemoryObjectSendStream, MemoryObjectStreamStatistics, _MemoryObjectItemReceiver, _MemoryObjectStreamState; 20 imports; method: MemoryObjectReceiveStream.__del__, MemoryObjectReceiveStream.__enter__, MemoryObjectReceiveStream.__exit__, MemoryObjectReceiveStream.__post_init__, MemoryObjectReceiveStream.aclose, MemoryObjectReceiveStream.clone; module: memory
**stapled.py** — class: MultiListener, StapledByteStream, StapledObjectStream; 17 imports; method: MultiListener.__post_init__, MultiListener.aclose, MultiListener.extra_attributes, MultiListener.serve, StapledByteStream.aclose, StapledByteStream.extra_attributes; module: stapled
**text.py** — class: TextConnectable, TextReceiveStream, TextSendStream, TextStream; 19 imports; method: TextConnectable.__init__, TextConnectable.connect, TextReceiveStream.__post_init__, TextReceiveStream.aclose, TextReceiveStream.extra_attributes, TextReceiveStream.receive; module: text
**tls.py** — class: TLSAttribute, TLSConnectable, TLSListener, TLSStream; 33 imports; method: TLSConnectable.__init__, TLSConnectable.connect, TLSListener.aclose, TLSListener.extra_attributes, TLSListener.handle_handshake_error, TLSListener.serve; module: tls
**to_interpreter.py** — function: _stop_workers, current_default_interpreter_limiter, run_sync; 23 imports; module: to_interpreter
**to_process.py** — function: current_default_process_limiter, process_worker, run_sync; 29 imports; module: to_process
**to_thread.py** — function: current_default_thread_limiter, run_sync; 11 imports; module: to_thread
**__init__.py** — class: AttrsInstance; function: _make_getattr; 35 imports; module: __init__
**_cmp.py** — function: _check_same_type, _is_comparable_to, _make_init, _make_operator, cmp_using; 3 imports; module: _cmp
**_compat.py** — class: _AnnotationExtractor; function: get_generic_base; 8 imports; method: _AnnotationExtractor.__init__, _AnnotationExtractor.get_first_param_type, _AnnotationExtractor.get_return_type; module: _compat
**_config.py** — function: get_run_validators, set_run_validators; module: _config
**_funcs.py** — function: _asdict_anything, asdict, assoc, astuple, has, resolve_types; 7 imports; module: _funcs
**_make.py** — class: Attribute, ClassProps, Converter, Factory, _AndValidator, _Attributes; function: __ne__, _add_eq, _add_hash, _add_repr, _assign, _assign_with_converter; 32 imports; method: Attribute.__getstate__, Attribute.__init__, Attribute.__setattr__, Attribute.__setstate__, Attribute._setattrs, Attribute.evolve; module: _make; rationale: [XXX] OK with us., [XXX] This can be confused by subclassing a slotted attrs class with, [XXX] a non-attrs class and subclass the resulting class with an attrs, [XXX] class.  See `test_slotted_confused` for details.  For now that's, [XXX] unused, remove along with other cmp code.
**_next_gen.py** — function: asdict, astuple, define, field, inspect; 11 imports; module: _next_gen
**_version_info.py** — class: VersionInfo; 4 imports; method: VersionInfo.__eq__, VersionInfo.__hash__, VersionInfo.__lt__, VersionInfo._ensure_tuple, VersionInfo._from_version_string; module: _version_info
**converters.py** — function: default_if_none, optional, to_bool; 6 imports; module: converters
**exceptions.py** — class: AttrsAttributeNotFoundError, DefaultAlreadySetError, FrozenAttributeError, FrozenError, FrozenInstanceError, NotAnAttrsClassError; 1 imports; method: FrozenError.__init__, NotCallableError.__init__, NotCallableError.__str__; module: exceptions
**filters.py** — function: _split_what, exclude, include; 1 imports; module: filters
**setters.py** — function: convert, frozen, pipe, validate; 3 imports; module: setters
**validators.py** — class: _DeepIterable, _DeepMapping, _InValidator, _InstanceOfValidator, _IsCallableValidator, _MatchesReValidator; function: _subclass_of, deep_iterable, deep_mapping, disabled, ge, get_disabled; 12 imports; method: _DeepIterable.__call__, _DeepIterable.__repr__, _DeepMapping.__call__, _DeepMapping.__repr__, _InValidator.__call__, _InValidator.__repr__; module: validators
**__init__.py** — 29 imports; module: __init__
**converters.py** — 1 imports; module: converters
**exceptions.py** — 1 imports; module: exceptions
**filters.py** — 1 imports; module: filters
**setters.py** — 1 imports; module: setters
**validators.py** — 1 imports; module: validators
**__init__.py** — 2 imports; module: __init__
**__main__.py** — 3 imports; module: __main__
**core.py** — function: exit_cacert_ctx; 6 imports; module: core
**__init__.py** — 6 imports; module: __init__
**_cffi_gen_src.py** — function: _execfile, _prog, exec_python, find_ffi_in_python_script, generate_c_source, make_ffi_from_sources; 5 imports; module: _cffi_gen_src
**_imp_emulation.py** — 10 imports; module: _imp_emulation
**_shimmed_dist_utils.py** — 15 imports; module: _shimmed_dist_utils
**api.py** — class: FFI; function: _builtin_function_type, _load_backend_lib, _make_ffi_library; 18 imports; method: FFI.__init__, FFI._apply_embedding_fix, FFI._apply_windows_unicode, FFI._cdef, FFI._get_cached_btype, FFI._get_errno; module: api
**backend_ctypes.py** — class: CTypesBackend, CTypesBaseStructOrUnion, CTypesData, CTypesGenericArray, CTypesGenericPrimitive, CTypesGenericPtr; 7 imports; method: CTypesBackend.__init__, CTypesBackend._get_types, CTypesBackend._new_struct_or_union, CTypesBackend.alignof, CTypesBackend.buffer, CTypesBackend.callback; module: backend_ctypes
**cffi_opcode.py** — class: CffiOp; function: format_four_bytes; 1 imports; method: CffiOp.__init__, CffiOp.__str__, CffiOp.as_c_expr, CffiOp.as_python_bytes; module: cffi_opcode
**commontypes.py** — function: resolve_common_type, win_common_types; 4 imports; module: commontypes
**cparser.py** — class: Parser; function: _common_type_names, _get_parser, _preprocess, _preprocess_extern_python, _put_back_line_directives, _remove_line_directives; 15 imports; method: Parser.__init__, Parser._add_constants, Parser._add_integer_constant, Parser._as_func_arg, Parser._build_enum_type, Parser._c_div; module: cparser; rationale: [HACK] `extern "Python"` in the C source is replaced, [NOTE] not for 'long double' so far, [XXX] for more efficiency we would need to poke into the
**error.py** — class: CDefError, FFIError, PkgConfigError, VerificationError, VerificationMissing; method: CDefError.__str__; module: error
**ffiplatform.py** — function: _build, _flatten, compile, flatten, get_extension, maybe_relative_path; 12 imports; module: ffiplatform
**gen_src.py** — 1 imports; module: gen_src
**lock.py** — 5 imports; module: lock
**model.py** — class: ArrayType, BaseFunctionType, BasePrimitiveType, BaseType, BaseTypeByIdentity, EnumType; function: ConstPointerType, attach_exception_info, get_typecache, global_cache, pointer_cache, qualify; 7 imports; method: ArrayType.__init__, ArrayType.build_backend_type, ArrayType.length_is_unknown, ArrayType.resolve_length, BaseFunctionType.__init__, BasePrimitiveType.is_complex_type; module: model
**pkgconfig.py** — function: call, flags_from_pkgconfig, merge_flags; 4 imports; module: pkgconfig
**recompiler.py** — class: EnumExpr, FieldExpr, GlobalExpr, Recompiler, StructUnionExpr, TypenameExpr; function: _is_file_like, _make_c_or_py_source, _modname_to_file, _patch_for_embedding, _patch_for_target, _patch_meth; 11 imports; method: EnumExpr.__init__, EnumExpr.as_c_expr, EnumExpr.as_python_expr, FieldExpr.__init__, FieldExpr.as_c_expr, FieldExpr.as_field_python_expr; module: recompiler
**setuptools_ext.py** — function: _add_c_module, _add_py_module, _set_py_limited_api, add_cffi_module, cffi_modules, error; 12 imports; module: setuptools_ext
**vengine_cpy.py** — class: VCPythonEngine; 5 imports; method: VCPythonEngine.__init__, VCPythonEngine._check_int_constant_value, VCPythonEngine._convert_expr_from_c, VCPythonEngine._convert_funcarg_to_c, VCPythonEngine._convert_funcarg_to_c_ptr_or_array, VCPythonEngine._do_collect_type; module: vengine_cpy
**vengine_gen.py** — class: VGenericEngine; 5 imports; method: VGenericEngine.__init__, VGenericEngine._check_int_constant_value, VGenericEngine._enum_funcname, VGenericEngine._generate, VGenericEngine._generate_gen_anonymous_decl, VGenericEngine._generate_gen_const; module: vengine_gen
**verifier.py** — class: Verifier; function: _caller_dir_pycache, _ensure_dir, _get_so_suffixes, _locate_engine_class, cleanup_tmpdir, set_tmpdir; 13 imports; method: Verifier.__init__, Verifier._compile_module, Verifier._load_library, Verifier._locate_module, Verifier._write_source, Verifier._write_source_to; module: verifier
**__init__.py** — function: __getattr__; 69 imports; module: __init__
**_compat.py** — class: _AtomicFile, _FixupStream, _NonClosingTextIOWrapper; function: _find_binary_reader, _find_binary_writer, _force_correct_text_reader, _force_correct_text_stream, _force_correct_text_writer, _is_binary_reader; 15 imports; method: _AtomicFile.__enter__, _AtomicFile.__exit__, _AtomicFile.__getattr__, _AtomicFile.__init__, _AtomicFile.__repr__, _AtomicFile.close; module: _compat; rationale: [NOTE] double check is needed so mypy does not analyze this on Linux
**_termui_impl.py** — class: Editor, ProgressBar; function: _nullpager, _pipepager, _tempfilepager, _translate_ch_to_exc, open_url, pager; 33 imports; method: Editor.__init__, Editor.edit, Editor.edit_files, Editor.get_editor, ProgressBar.__enter__, ProgressBar.__exit__; module: _termui_impl; rationale: [TODO] This never terminates if the passed generator never terminates.
**_textwrap.py** — class: TextWrapper; 4 imports; method: TextWrapper._handle_long_word, TextWrapper.extra_indent, TextWrapper.indent_only; module: _textwrap
**_utils.py** — class: Sentinel; 3 imports; method: Sentinel.__repr__; module: _utils
**_winconsole.py** — class: ConsoleStream, _WindowsConsoleRawIOBase, _WindowsConsoleReader, _WindowsConsoleWriter; function: _get_text_stderr, _get_text_stdin, _get_text_stdout, _get_windows_console_stream, _is_console; 28 imports; method: ConsoleStream.__getattr__, ConsoleStream.__init__, ConsoleStream.__repr__, ConsoleStream.isatty, ConsoleStream.name, ConsoleStream.write; module: _winconsole
**core.py** — class: Argument, Command, CommandCollection, Context, Group, Option; function: __getattr__, _check_iter, _check_nested_chain, _complete_visible_commands, augment_usage_errors, batch; 49 imports; method: Argument.__init__, Argument._parse_decls, Argument.add_to_parser, Argument.get_error_hint, Argument.get_usage_pieces, Argument.human_readable_name; module: core
**decorators.py** — function: _param_memo, argument, command, confirmation_option, group, help_option; 15 imports; module: decorators
**exceptions.py** — class: Abort, BadArgumentUsage, BadOptionUsage, BadParameter, ClickException, Exit; function: _join_param_hints; 12 imports; method: BadOptionUsage.__init__, BadParameter.__init__, BadParameter.format_message, ClickException.__init__, ClickException.__str__, ClickException.format_message; module: exceptions
**formatting.py** — class: HelpFormatter; function: iter_rows, join_options, measure_table, wrap_text; 8 imports; method: HelpFormatter.__init__, HelpFormatter.dedent, HelpFormatter.getvalue, HelpFormatter.indent, HelpFormatter.indentation, HelpFormatter.section; module: formatting
**globals.py** — function: get_current_context, pop_context, push_context, resolve_color_default; 4 imports; module: globals
**parser.py** — class: _Argument, _Option, _OptionParser, _ParsingState; function: __getattr__, _normalize_opt, _split_opt, _unpack_args; 21 imports; method: _Argument.__init__, _Argument.process, _Option.__init__, _Option.process, _Option.takes_value, _OptionParser.__init__; module: parser
**shell_completion.py** — class: BashComplete, CompletionItem, FishComplete, ShellComplete, ZshComplete; function: _is_incomplete_argument, _is_incomplete_option, _resolve_context, _resolve_incomplete, _start_of_option, add_completion_class; 17 imports; method: BashComplete._check_version, BashComplete.format_completion, BashComplete.get_completion_args, BashComplete.source, CompletionItem.__getattr__, CompletionItem.__init__; module: shell_completion
**termui.py** — function: _build_prompt, _format_default, _interpret_color, clear, confirm, echo_via_pager; 26 imports; module: termui
**testing.py** — class: BytesIOCopy, CliRunner, EchoingStdin, Result, StreamMixer, _NamedTextIOWrapper; function: _pause_echo, make_input_stream; 19 imports; method: BytesIOCopy.__init__, BytesIOCopy.flush, BytesIOCopy.write, CliRunner.__init__, CliRunner.get_default_prog_name, CliRunner.invoke; module: testing
**types.py** — class: BoolParamType, Choice, CompositeParamType, DateTime, File, FloatParamType; function: _is_file_like, convert_type; 23 imports; method: BoolParamType.__repr__, BoolParamType.convert, BoolParamType.str_to_bool, Choice.__init__, Choice.__repr__, Choice._normalized_mapping; module: types
**utils.py** — class: KeepOpenFile, LazyFile, PacifyFlushWrapper; function: _detect_program_name, _expand_args, _posixify, echo, format_filename, get_app_dir; 24 imports; method: KeepOpenFile.__enter__, KeepOpenFile.__exit__, KeepOpenFile.__getattr__, KeepOpenFile.__init__, KeepOpenFile.__iter__, KeepOpenFile.__repr__; module: utils
**__init__.py** — 10 imports; module: __init__
**ansi.py** — class: AnsiBack, AnsiCodes, AnsiCursor, AnsiFore, AnsiStyle; function: clear_line, clear_screen, code_to_chars, set_title; method: AnsiCodes.__init__, AnsiCursor.BACK, AnsiCursor.DOWN, AnsiCursor.FORWARD, AnsiCursor.POS, AnsiCursor.UP; module: ansi
**ansitowin32.py** — class: AnsiToWin32, StreamWrapper; 14 imports; method: AnsiToWin32.__init__, AnsiToWin32.call_win32, AnsiToWin32.convert_ansi, AnsiToWin32.convert_osc, AnsiToWin32.extract_params, AnsiToWin32.flush; module: ansitowin32
**initialise.py** — function: _wipe_internal_state_for_tests, colorama_text, deinit, init, just_fix_windows_console, reinit; 4 imports; module: initialise
**__init__.py** — module: __init__
**ansi_test.py** — class: AnsiTest; 7 imports; method: AnsiTest.setUp, AnsiTest.tearDown, AnsiTest.testBackAttributes, AnsiTest.testForeAttributes, AnsiTest.testStyleAttributes; module: ansi_test
**ansitowin32_test.py** — class: AnsiToWin32Test, StreamWrapperTest; 16 imports; method: AnsiToWin32Test.assert_autoresets, AnsiToWin32Test.testCallWin32UsesLookup, AnsiToWin32Test.testExtractParams, AnsiToWin32Test.testInit, AnsiToWin32Test.testStripIsFalseOffWindows, AnsiToWin32Test.testStripIsTrueOnWindows; module: ansitowin32_test
**initialise_test.py** — class: InitTest, JustFixWindowsConsoleTest; 14 imports; method: InitTest.assertNotWrapped, InitTest.assertWrapped, InitTest.setUp, InitTest.tearDown, InitTest.testAtexitRegisteredOnlyOnce, InitTest.testAutoResetChangeable; module: initialise_test
**isatty_test.py** — class: IsattyTest; function: is_a_tty; 10 imports; method: IsattyTest.test_TTY, IsattyTest.test_nonTTY, IsattyTest.test_withPycharm, IsattyTest.test_withPycharmNonTTYOverride, IsattyTest.test_withPycharmNoneOverride, IsattyTest.test_withPycharmStreamWrapped; module: isatty_test
**utils.py** — class: StreamNonTTY, StreamTTY; function: osname, pycharm, replace_by, replace_original_by; 4 imports; method: StreamNonTTY.isatty, StreamTTY.isatty; module: utils
**winterm_test.py** — class: WinTermTest; 11 imports; method: WinTermTest.testBack, WinTermTest.testFore, WinTermTest.testGetAttrs, WinTermTest.testInit, WinTermTest.testResetAll, WinTermTest.testSetConsole; module: winterm_test
**win32.py** — 7 imports; module: win32
**winterm.py** — class: WinColor, WinStyle, WinTerm; function: enable_vt_processing; 2 imports; method: WinTerm.__init__, WinTerm.back, WinTerm.cursor_adjust, WinTerm.erase_line, WinTerm.erase_screen, WinTerm.fore; module: winterm
**__about__.py** — 1 imports; module: __about__
**__init__.py** — 4 imports; module: __init__
**exceptions.py** — class: AlreadyFinalized, AlreadyUpdated, InternalError, InvalidKey, InvalidSignature, InvalidTag; 4 imports; method: InternalError.__init__, UnsupportedAlgorithm.__init__; module: exceptions
**fernet.py** — class: Fernet, InvalidToken, MultiFernet; 15 imports; method: Fernet.__init__, Fernet._decrypt_data, Fernet._encrypt_from_parts, Fernet._get_unverified_token_data, Fernet._verify_signature, Fernet.decrypt; module: fernet
**__init__.py** — 1 imports; module: __init__
**_oid.py** — class: AttributeOID, AuthorityInformationAccessOID, CRLEntryExtensionOID, CertificatePoliciesOID, ExtendedKeyUsageOID, ExtensionOID; 3 imports; module: _oid
**__init__.py** — 18 imports; module: __init__
**asn1.py** — class: Default, Variant; function: _annotate_fields, _check_x509_field_annotations, _extract_annotation, _is_union, _normalize_field_type, _register_asn1_sequence; 10 imports; module: asn1; rationale: [NOTE] types.UnionType for `T | U`, typing.Union for `Union[T, U]`., [TODO] Drop the `hasattr()` once the minimum supported Python version, [TODO] replace with `Default[U]` once the min Python version is >= 3.12
**__init__.py** — function: default_backend; 3 imports; module: __init__
**__init__.py** — 2 imports; module: __init__
**backend.py** — class: Backend; 15 imports; method: Backend.__init__, Backend.__repr__, Backend._consume_errors, Backend._enable_fips, Backend._oaep_hash_supported, Backend.argon2_supported; module: backend
**__init__.py** — module: __init__
**__init__.py** — module: __init__
**_conditional.py** — function: cryptography_has_custom_ext, cryptography_has_dtls_get_data_mtu, cryptography_has_engine, cryptography_has_get_extms_support, cryptography_has_prime_checks, cryptography_has_psk; 1 imports; module: _conditional
**binding.py** — class: Binding; function: _openssl_assert, _verify_package_version, build_conditional_library; 11 imports; method: Binding.__init__, Binding._ensure_ffi_initialized, Binding.init_static_locks; module: binding
**__init__.py** — 1 imports; module: __init__
**__init__.py** — 1 imports; module: __init__
**algorithms.py** — class: ARC4, Blowfish, CAST5, Camellia, IDEA, RC2; 6 imports; method: ARC4.__init__, ARC4.key_size, Blowfish.__init__, Blowfish.key_size, CAST5.__init__, CAST5.key_size; module: algorithms
**modes.py** — class: CFB, CFB8, OFB; 4 imports; method: CFB.__init__, CFB.initialization_vector, CFB8.__init__, CFB8.initialization_vector, OFB.__init__, OFB.initialization_vector; module: modes
**__init__.py** — module: __init__
**_asymmetric.py** — class: AsymmetricPadding; 2 imports; method: AsymmetricPadding.name; module: _asymmetric
**_cipheralgorithm.py** — class: BlockCipherAlgorithm, CipherAlgorithm; function: _verify_key_size; 3 imports; method: BlockCipherAlgorithm.block_size, CipherAlgorithm.key_size, CipherAlgorithm.key_sizes, CipherAlgorithm.name; module: _cipheralgorithm
**_modes.py** — class: Mode, ModeWithAuthenticationTag, ModeWithInitializationVector, ModeWithNonce, ModeWithTweak; function: _check_aes_key_length, _check_iv_and_key_length, _check_iv_length, _check_nonce_length; 7 imports; method: Mode.name, Mode.validate_for_algorithm, ModeWithAuthenticationTag.tag, ModeWithInitializationVector.initialization_vector, ModeWithNonce.nonce, ModeWithTweak.tweak; module: _modes
**_serialization.py** — class: BestAvailableEncryption, KeySerializationEncryption, KeySerializationEncryptionBuilder, NoEncryption, PBES, _KeySerializationEncryption; 8 imports; method: BestAvailableEncryption.__init__, KeySerializationEncryptionBuilder.__init__, KeySerializationEncryptionBuilder.build, KeySerializationEncryptionBuilder.hmac_hash, KeySerializationEncryptionBuilder.kdf_rounds, KeySerializationEncryptionBuilder.key_cert_algorithm; module: _serialization
**__init__.py** — module: __init__
**dh.py** — class: DHParameters, DHPrivateKey, DHPublicKey; 4 imports; method: DHParameters.generate_private_key, DHParameters.parameter_bytes, DHParameters.parameter_numbers, DHPrivateKey.__copy__, DHPrivateKey.__deepcopy__, DHPrivateKey.exchange; module: dh
**dsa.py** — class: DSAParameters, DSAPrivateKey, DSAPublicKey; function: generate_parameters, generate_private_key; 8 imports; method: DSAParameters.generate_private_key, DSAParameters.parameter_numbers, DSAPrivateKey.__copy__, DSAPrivateKey.__deepcopy__, DSAPrivateKey.key_size, DSAPrivateKey.parameters; module: dsa
**ec.py** — class: BrainpoolP256R1, BrainpoolP384R1, BrainpoolP512R1, ECDH, ECDSA, EllipticCurve; function: derive_private_key, get_curve_for_oid; 12 imports; method: ECDSA.__init__, ECDSA.algorithm, ECDSA.deterministic_signing, EllipticCurve.group_order, EllipticCurve.key_size, EllipticCurve.name; module: ec
**ed25519.py** — class: Ed25519PrivateKey, Ed25519PublicKey; 5 imports; method: Ed25519PrivateKey.__copy__, Ed25519PrivateKey.__deepcopy__, Ed25519PrivateKey.from_private_bytes, Ed25519PrivateKey.generate, Ed25519PrivateKey.private_bytes, Ed25519PrivateKey.private_bytes_raw; module: ed25519
**ed448.py** — class: Ed448PrivateKey, Ed448PublicKey; 8 imports; method: Ed448PrivateKey.__copy__, Ed448PrivateKey.__deepcopy__, Ed448PrivateKey.from_private_bytes, Ed448PrivateKey.generate, Ed448PrivateKey.private_bytes, Ed448PrivateKey.private_bytes_raw; module: ed448
**mldsa.py** — class: MLDSA44PrivateKey, MLDSA44PublicKey, MLDSA65PrivateKey, MLDSA65PublicKey, MLDSA87PrivateKey, MLDSA87PublicKey; 8 imports; method: MLDSA44PrivateKey.__copy__, MLDSA44PrivateKey.__deepcopy__, MLDSA44PrivateKey.from_seed_bytes, MLDSA44PrivateKey.generate, MLDSA44PrivateKey.private_bytes, MLDSA44PrivateKey.private_bytes_raw; module: mldsa
**mlkem.py** — class: MLKEM1024PrivateKey, MLKEM1024PublicKey, MLKEM768PrivateKey, MLKEM768PublicKey; 8 imports; method: MLKEM1024PrivateKey.__copy__, MLKEM1024PrivateKey.__deepcopy__, MLKEM1024PrivateKey.decapsulate, MLKEM1024PrivateKey.from_seed_bytes, MLKEM1024PrivateKey.generate, MLKEM1024PrivateKey.private_bytes; module: mlkem
**padding.py** — class: MGF, MGF1, OAEP, PKCS1v15, PSS, _Auto; function: calculate_max_pss_salt_length; 5 imports; method: MGF1.__init__, OAEP.__init__, OAEP.algorithm, OAEP.mgf, PSS.__init__, PSS.mgf; module: padding
**rsa.py** — class: RSAPrivateKey, RSAPublicKey; function: _modinv, _verify_rsa_parameters, generate_private_key, rsa_crt_dmp1, rsa_crt_dmq1, rsa_crt_iqmp; 11 imports; method: RSAPrivateKey.__copy__, RSAPrivateKey.__deepcopy__, RSAPrivateKey.decrypt, RSAPrivateKey.key_size, RSAPrivateKey.private_bytes, RSAPrivateKey.private_numbers; module: rsa
**types.py** — 12 imports; module: types
**utils.py** — class: NoDigestInfo, Prehashed; 3 imports; method: Prehashed.__init__, Prehashed.digest_size; module: utils
**x25519.py** — class: X25519PrivateKey, X25519PublicKey; 8 imports; method: X25519PrivateKey.__copy__, X25519PrivateKey.__deepcopy__, X25519PrivateKey.exchange, X25519PrivateKey.from_private_bytes, X25519PrivateKey.generate, X25519PrivateKey.private_bytes; module: x25519
**x448.py** — class: X448PrivateKey, X448PublicKey; 8 imports; method: X448PrivateKey.__copy__, X448PrivateKey.__deepcopy__, X448PrivateKey.exchange, X448PrivateKey.from_private_bytes, X448PrivateKey.generate, X448PrivateKey.private_bytes; module: x448
**__init__.py** — 8 imports; module: __init__
**aead.py** — 2 imports; module: aead
**algorithms.py** — class: AES, AES128, AES256, ChaCha20, SM4; 12 imports; method: AES.__init__, AES.key_size, AES128.__init__, AES256.__init__, ChaCha20.__init__, ChaCha20.key_size; module: algorithms
**base.py** — class: AEADCipherContext, AEADDecryptionContext, AEADEncryptionContext, Cipher, CipherContext; 7 imports; method: AEADCipherContext.authenticate_additional_data, AEADDecryptionContext.finalize_with_tag, AEADEncryptionContext.tag, Cipher.__init__, Cipher.decryptor, Cipher.encryptor; module: base
**modes.py** — class: CBC, CTR, ECB, GCM, XTS; 18 imports; method: CBC.__init__, CBC.initialization_vector, CTR.__init__, CTR.nonce, CTR.validate_for_algorithm, GCM.__init__; module: modes
**cmac.py** — 2 imports; module: cmac
**constant_time.py** — function: bytes_eq; 2 imports; module: constant_time
**hashes.py** — class: BLAKE2b, BLAKE2s, ExtendableOutputFunction, HashAlgorithm, HashContext, MD5; 4 imports; method: BLAKE2b.__init__, BLAKE2b.digest_size, BLAKE2s.__init__, BLAKE2s.digest_size, HashAlgorithm.block_size, HashAlgorithm.digest_size; module: hashes
**hmac.py** — 3 imports; module: hmac
**hpke.py** — 2 imports; module: hpke
**__init__.py** — class: KeyDerivationFunction; 3 imports; method: KeyDerivationFunction.derive, KeyDerivationFunction.derive_into, KeyDerivationFunction.verify; module: __init__
**argon2.py** — 3 imports; module: argon2
**concatkdf.py** — 3 imports; module: concatkdf
**hkdf.py** — 3 imports; module: hkdf
**kbkdf.py** — class: CounterLocation, Mode; 4 imports; module: kbkdf
**pbkdf2.py** — 3 imports; module: pbkdf2
**scrypt.py** — 4 imports; module: scrypt
**x963kdf.py** — 3 imports; module: x963kdf
**keywrap.py** — class: InvalidUnwrap; function: _unwrap_core, _wrap_core, aes_key_unwrap, aes_key_unwrap_with_padding, aes_key_wrap, aes_key_wrap_with_padding; 6 imports; module: keywrap
**padding.py** — class: ANSIX923, PKCS7, PaddingContext; function: _byte_padding_check; 7 imports; method: ANSIX923.__init__, ANSIX923.padder, ANSIX923.unpadder, PKCS7.__init__, PKCS7.padder, PKCS7.unpadder; module: padding
**poly1305.py** — 2 imports; module: poly1305
**__init__.py** — 26 imports; module: __init__
**base.py** — 1 imports; module: base
**pkcs12.py** — class: PKCS12KeyAndCertificates; function: serialize_java_truststore, serialize_key_and_certificates; 13 imports; method: PKCS12KeyAndCertificates.__eq__, PKCS12KeyAndCertificates.__hash__, PKCS12KeyAndCertificates.__init__, PKCS12KeyAndCertificates.__repr__, PKCS12KeyAndCertificates.additional_certs, PKCS12KeyAndCertificates.cert; module: pkcs12
**pkcs7.py** — class: OpenSSLMimePart, PKCS7EnvelopeBuilder, PKCS7Options, PKCS7SignatureBuilder; function: _smime_enveloped_decode, _smime_enveloped_encode, _smime_remove_text_headers, _smime_signed_encode; 21 imports; method: OpenSSLMimePart._write_headers, PKCS7EnvelopeBuilder.__init__, PKCS7EnvelopeBuilder.add_recipient, PKCS7EnvelopeBuilder.encrypt, PKCS7EnvelopeBuilder.set_content_encryption_algorithm, PKCS7EnvelopeBuilder.set_data; module: pkcs7
**ssh.py** — class: SSHCertificate, SSHCertificateBuilder, SSHCertificateType, _FragList, _SSHCipher, _SSHFormatDSA; function: _check_block_size, _check_empty, _ecdsa_key_type, _get_ec_hash_alg, _get_mpint, _get_ssh_key_type; 29 imports; method: SSHCertificate.__init__, SSHCertificate.critical_options, SSHCertificate.extensions, SSHCertificate.key_id, SSHCertificate.nonce, SSHCertificate.public_bytes; module: ssh
**__init__.py** — class: InvalidToken; 1 imports; module: __init__
**hotp.py** — class: HOTP; function: _generate_uri; 12 imports; method: HOTP.__init__, HOTP._dynamic_truncate, HOTP.generate, HOTP.get_provisioning_uri, HOTP.verify; module: hotp
**totp.py** — class: TOTP; 8 imports; method: TOTP.__init__, TOTP.generate, TOTP.get_provisioning_uri, TOTP.verify; module: totp
**utils.py** — class: CryptographyDeprecationWarning, Enum, InterfaceNotImplemented, _DeprecatedValue, _ModuleWithDeprecations; function: _check_bytes, _check_byteslike, cached_property, deprecated, int_to_bytes; 8 imports; method: Enum.__repr__, Enum.__str__, _DeprecatedValue.__init__, _ModuleWithDeprecations.__delattr__, _ModuleWithDeprecations.__dir__, _ModuleWithDeprecations.__getattr__; module: utils
**__init__.py** — 94 imports; module: __init__
**base.py** — class: Attribute, AttributeNotFound, Attributes, CertificateBuilder, CertificateRevocationListBuilder, CertificateSigningRequestBuilder; function: _convert_to_naive_utc_time, _reject_duplicate_attribute, _reject_duplicate_extension, random_serial_number; 25 imports; method: Attribute.__eq__, Attribute.__hash__, Attribute.__init__, Attribute.__repr__, Attribute.oid, Attribute.value; module: base
**certificate_transparency.py** — class: LogEntryType, SignatureAlgorithm, Version; 3 imports; module: certificate_transparency
**extensions.py** — class: AccessDescription, Admission, Admissions, AuthorityInformationAccess, AuthorityKeyIdentifier, BasicConstraints; function: _key_identifier_from_public_key, _make_sequence_methods; 33 imports; method: AccessDescription.__eq__, AccessDescription.__hash__, AccessDescription.__init__, AccessDescription.__repr__, AccessDescription.access_location, AccessDescription.access_method; module: extensions
**general_name.py** — class: DNSName, DirectoryName, GeneralName, IPAddress, OtherName, RFC822Name; 7 imports; method: DNSName.__eq__, DNSName.__hash__, DNSName.__init__, DNSName.__repr__, DNSName._init_without_validation, DNSName.value; module: general_name
**name.py** — class: Name, NameAttribute, RelativeDistinguishedName, _ASN1Type, _RFC4514NameParser; function: _escape_dn_value, _unescape_dn_value; 12 imports; method: Name.__eq__, Name.__hash__, Name.__init__, Name.__iter__, Name.__len__, Name.__repr__; module: name; rationale: [TODO] this is relatively expensive, if this looks like a bottleneck
**ocsp.py** — class: OCSPCertStatus, OCSPRequestBuilder, OCSPResponderEncoding, OCSPResponseBuilder, OCSPResponseStatus, _SingleResponse; function: _verify_algorithm; 9 imports; method: OCSPRequestBuilder.__init__, OCSPRequestBuilder.add_certificate, OCSPRequestBuilder.add_certificate_by_hash, OCSPRequestBuilder.add_extension, OCSPRequestBuilder.build, OCSPResponseBuilder.__init__; module: ocsp
**oid.py** — 14 imports; module: oid
**verification.py** — 5 imports; module: verification
**__init__.py** — function: get_cli_string, load_ipython_extension; 9 imports; module: __init__
**__main__.py** — 1 imports; module: __main__
**cli.py** — function: cli, enumerate_env, get, list_values, run, run_command; 17 imports; module: cli
**ipython.py** — class: IPythonDotEnv; function: load_ipython_extension; 8 imports; method: IPythonDotEnv.dotenv; module: ipython
**main.py** — class: DotEnv; function: _is_file_or_fifo, _load_dotenv_disabled, _walk_to_root, dotenv_values, find_dotenv, get_key; 20 imports; method: DotEnv.__init__, DotEnv._get_stream, DotEnv.dict, DotEnv.get, DotEnv.parse, DotEnv.set_as_environment_variables; module: main
**parser.py** — class: Binding, Error, Original, Position, Reader; function: decode_escapes, make_regex, parse_binding, parse_key, parse_stream, parse_unquoted_value; 9 imports; method: Position.__init__, Position.advance, Position.set, Position.start, Reader.__init__, Reader.get_marked; module: parser
**variables.py** — class: Atom, Literal, Variable; function: parse_variables; 7 imports; method: Atom.__ne__, Atom.resolve, Literal.__eq__, Literal.__hash__, Literal.__init__, Literal.__repr__; module: variables
**version.py** — module: version
**__init__.py** — 20 imports; module: __init__
**__main__.py** — 1 imports; module: __main__
**__init__.py** — 30 imports; module: __init__
**shared.py** — function: _annotation_is_complex, _annotation_is_sequence, annotation_is_pydantic_v1, field_annotation_is_complex, field_annotation_is_scalar, field_annotation_is_scalar_sequence; 19 imports; module: shared; rationale: [TODO] remove this function once the required version of Pydantic fully, [TODO] remove this function once the required version of Pydantic fully
**v2.py** — class: GenerateJsonSchema, ModelField; function: _has_computed_fields, _regenerate_error_with_loc, asdict, copy_field_info, create_body_model, evaluate_forwardref; 40 imports; method: GenerateJsonSchema.bytes_schema, ModelField.__hash__, ModelField.__post_init__, ModelField.alias, ModelField.default, ModelField.get_default; module: v2; rationale: [TODO] remove after setting the min Pydantic to v2.12.3, [TODO] remove when dropping support for Pydantic < v2.12.3, [TODO] remove when dropping support for Pydantic < v2.12.3, [TODO] remove when this is merged (or equivalent): https://github.com/pydantic/pydantic
**applications.py** — class: FastAPI; 46 imports; method: FastAPI.__call__, FastAPI.__init__, FastAPI.add_api_route, FastAPI.add_api_websocket_route, FastAPI.api_route, FastAPI.build_middleware_stack; module: applications; rationale: [TODO] remove when discarding the openapi_prefix parameter
**background.py** — class: BackgroundTasks; 6 imports; method: BackgroundTasks.add_task; module: background
**cli.py** — function: main; 1 imports; module: cli
**concurrency.py** — function: contextmanager_in_threadpool; 9 imports; module: concurrency
**datastructures.py** — class: DefaultPlaceholder, UploadFile; function: Default; 17 imports; method: DefaultPlaceholder.__bool__, DefaultPlaceholder.__eq__, DefaultPlaceholder.__init__, UploadFile.__get_pydantic_core_schema__, UploadFile.__get_pydantic_json_schema__, UploadFile._validate; module: datastructures
**models.py** — class: Dependant; function: _impartial, _unwrapped_call; 14 imports; method: Dependant._is_security_scheme, Dependant._security_dependencies, Dependant._security_scheme, Dependant._uses_scopes, Dependant.cache_key, Dependant.computed_scope; module: models
**utils.py** — class: ParamDetails, SolvedDependency; function: _extract_form_body, _get_flat_fields_from_params, _get_multidict_value, _get_signature, _is_json_field, _should_embed_body_fields; 76 imports; module: utils; rationale: [TODO] remove this parameter later, no longer used, not removing it yet as some
**encoders.py** — function: decimal_encoder, generate_encoders_by_class_tuples, isoformat, jsonable_encoder; 33 imports; module: encoders; rationale: [TODO] pv2 should this return strings instead?
**exception_handlers.py** — function: http_exception_handler, request_validation_exception_handler, websocket_request_validation_exception_handler; 10 imports; module: exception_handlers
**exceptions.py** — class: DependencyScopeError, EndpointContext, FastAPIDeprecationWarning, FastAPIError, HTTPException, PydanticV1NotSupportedError; 10 imports; method: HTTPException.__init__, RequestValidationError.__init__, ResponseValidationError.__init__, ValidationException.__init__, ValidationException.__str__, ValidationException._format_endpoint_context; module: exceptions
**logger.py** — 1 imports; module: logger
**__init__.py** — 1 imports; module: __init__
**asyncexitstack.py** — class: AsyncExitStackMiddleware; 5 imports; method: AsyncExitStackMiddleware.__call__, AsyncExitStackMiddleware.__init__; module: asyncexitstack
**cors.py** — 1 imports; module: cors
**gzip.py** — 1 imports; module: gzip
**httpsredirect.py** — 1 imports; module: httpsredirect
**trustedhost.py** — 1 imports; module: trustedhost
**wsgi.py** — 1 imports; module: wsgi
**constants.py** — module: constants
**docs.py** — function: _html_safe_json, get_redoc_html, get_swagger_ui_html, get_swagger_ui_oauth2_redirect_html; 6 imports; module: docs
**models.py** — class: APIKey, APIKeyIn, BaseModelWithConfig, Components, Contact, Discriminator; 19 imports; module: models
**utils.py** — function: _get_openapi_operation_parameters, generate_operation_id, generate_operation_summary, get_fields_from_routes, get_openapi, get_openapi_operation_metadata; 38 imports; module: utils; rationale: [TODO] probably make status_code a default class attribute for all
**param_functions.py** — function: Body, Cookie, Depends, File, Form, Header; 13 imports; module: param_functions
**params.py** — class: Body, Cookie, Depends, File, Form, Header; 16 imports; method: Body.__init__, Body.__repr__, Cookie.__init__, File.__init__, Form.__init__, Header.__init__; module: params
**requests.py** — 2 imports; module: requests
**responses.py** — class: ORJSONResponse, UJSONResponse, _OrjsonModule, _UjsonModule; 14 imports; method: ORJSONResponse.render, UJSONResponse.render, _OrjsonModule.dumps, _UjsonModule.dumps; module: responses
**routing.py** — class: APIRoute, APIRouter, APIWebSocketRoute, _AsyncLiftContextManager, _DefaultLifespan; function: _build_response_args, _extract_endpoint_context, _merge_lifespan_context, _wrap_gen_lifespan_context, get_request_handler, get_websocket_app; 84 imports; method: APIRoute.__init__, APIRoute.get_route_handler, APIRoute.matches, APIRouter.__init__, APIRouter._shutdown, APIRouter._startup; module: routing; rationale: [TODO] deprecate this once the lifespan (or alternative) interface is improved, [TODO] remove this once the lifespan (or alternative) interface is improved, [TODO] remove this once the lifespan (or alternative) interface is improved, [TODO] remove this once the lifespan (or alternative) interface is improved
**__init__.py** — 15 imports; module: __init__
**api_key.py** — class: APIKeyBase, APIKeyCookie, APIKeyHeader, APIKeyQuery; 8 imports; method: APIKeyBase.__init__, APIKeyBase.check_api_key, APIKeyBase.make_not_authenticated_error, APIKeyCookie.__call__, APIKeyCookie.__init__, APIKeyHeader.__call__; module: api_key
**base.py** — class: SecurityBase; 1 imports; module: base
**http.py** — class: HTTPAuthorizationCredentials, HTTPBase, HTTPBasic, HTTPBasicCredentials, HTTPBearer, HTTPDigest; 12 imports; method: HTTPBase.__call__, HTTPBase.__init__, HTTPBase.make_authenticate_headers, HTTPBase.make_not_authenticated_error, HTTPBasic.__call__, HTTPBasic.__init__; module: http
**oauth2.py** — class: OAuth2, OAuth2AuthorizationCodeBearer, OAuth2PasswordBearer, OAuth2PasswordRequestForm, OAuth2PasswordRequestFormStrict, SecurityScopes; 12 imports; method: OAuth2.__call__, OAuth2.__init__, OAuth2.make_not_authenticated_error, OAuth2AuthorizationCodeBearer.__call__, OAuth2AuthorizationCodeBearer.__init__, OAuth2PasswordBearer.__call__; module: oauth2
**open_id_connect_url.py** — class: OpenIdConnect; 7 imports; method: OpenIdConnect.__call__, OpenIdConnect.__init__, OpenIdConnect.make_not_authenticated_error; module: open_id_connect_url
**utils.py** — function: get_authorization_scheme_param; module: utils
**sse.py** — class: EventSourceResponse, ServerSentEvent; function: _check_id_no_null, format_sse_event; 8 imports; method: ServerSentEvent._check_data_exclusive; module: sse
**staticfiles.py** — 1 imports; module: staticfiles
**templating.py** — 1 imports; module: templating
**testclient.py** — 1 imports; module: testclient
**types.py** — 8 imports; module: types
**utils.py** — function: create_model_field, deep_dict_update, generate_operation_id_for_path, generate_unique_id, get_path_param_names, get_value_or_default; 17 imports; module: utils
**websockets.py** — 3 imports; module: websockets
**__init__.py** — 25 imports; module: __init__
**_abnf.py** — module: _abnf
**_connection.py** — class: Connection, NEED_DATA, PAUSED; function: _body_framing, _keep_alive; 38 imports; method: Connection.__init__, Connection._clean_up_response_headers_for_sending, Connection._extract_next_receive_event, Connection._get_io_object, Connection._process_error, Connection._process_event; module: _connection
**_events.py** — class: ConnectionClosed, Data, EndOfMessage, Event, InformationalResponse, Request; 13 imports; method: Data.__init__, EndOfMessage.__init__, InformationalResponse.__post_init__, Request.__init__, Response.__post_init__, _ResponseBase.__init__; module: _events
**_headers.py** — class: Headers; function: get_comma_header, has_expect_100_continue, normalize_and_validate, set_comma_header; 17 imports; method: Headers.__bool__, Headers.__eq__, Headers.__getitem__, Headers.__init__, Headers.__len__, Headers.__repr__; module: _headers
**_readers.py** — class: ChunkedReader, ContentLengthReader, Http10Reader; function: _decode_header_lines, _obsolete_line_fold, expect_nothing, maybe_read_from_IDLE_client, maybe_read_from_SEND_RESPONSE_server; 32 imports; method: ChunkedReader.__call__, ChunkedReader.__init__, ChunkedReader.read_eof, ContentLengthReader.__call__, ContentLengthReader.__init__, ContentLengthReader.read_eof; module: _readers
**_receivebuffer.py** — class: ReceiveBuffer; 5 imports; method: ReceiveBuffer.__bool__, ReceiveBuffer.__bytes__, ReceiveBuffer.__iadd__, ReceiveBuffer.__init__, ReceiveBuffer.__len__, ReceiveBuffer._extract; module: _receivebuffer
**_state.py** — class: CLIENT, CLOSED, ConnectionState, DONE, ERROR, IDLE; 10 imports; method: ConnectionState.__init__, ConnectionState._fire_event_triggered_transitions, ConnectionState._fire_state_triggered_transitions, ConnectionState.process_client_switch_proposal, ConnectionState.process_error, ConnectionState.process_event; module: _state
**_util.py** — class: LocalProtocolError, ProtocolError, RemoteProtocolError, Sentinel; function: bytesify, validate; 8 imports; method: LocalProtocolError._reraise_as_remote_protocol_error, ProtocolError.__init__, Sentinel.__new__, Sentinel.__repr__; module: _util
**_version.py** — module: _version
**_writers.py** — class: BodyWriter, ChunkedWriter, ContentLengthWriter, Http10Writer; function: write_any_response, write_headers, write_request; 21 imports; method: BodyWriter.__call__, BodyWriter.send_data, BodyWriter.send_eom, ChunkedWriter.send_data, ChunkedWriter.send_eom, ContentLengthWriter.__init__; module: _writers
**__init__.py** — 49 imports; module: __init__
**_api.py** — function: request, stream; 8 imports; module: _api
**__init__.py** — 7 imports; module: __init__
**connection.py** — class: AsyncHTTPConnection; function: exponential_backoff; 21 imports; method: AsyncHTTPConnection.__aenter__, AsyncHTTPConnection.__aexit__, AsyncHTTPConnection.__init__, AsyncHTTPConnection.__repr__, AsyncHTTPConnection._connect, AsyncHTTPConnection.aclose; module: connection
**connection_pool.py** — class: AsyncConnectionPool, AsyncPoolRequest, PoolByteStream; 23 imports; method: AsyncConnectionPool.__aenter__, AsyncConnectionPool.__aexit__, AsyncConnectionPool.__init__, AsyncConnectionPool.__repr__, AsyncConnectionPool._assign_requests_to_connections, AsyncConnectionPool._close_connections; module: connection_pool
**http11.py** — class: AsyncHTTP11Connection, AsyncHTTP11UpgradeStream, HTTP11ConnectionByteStream, HTTPConnectionState; 21 imports; method: AsyncHTTP11Connection.__aenter__, AsyncHTTP11Connection.__aexit__, AsyncHTTP11Connection.__init__, AsyncHTTP11Connection.__repr__, AsyncHTTP11Connection._receive_event, AsyncHTTP11Connection._receive_response_body; module: http11
**http2.py** — class: AsyncHTTP2Connection, HTTP2ConnectionByteStream, HTTPConnectionState; function: has_body_headers; 23 imports; method: AsyncHTTP2Connection.__aenter__, AsyncHTTP2Connection.__aexit__, AsyncHTTP2Connection.__init__, AsyncHTTP2Connection.__repr__, AsyncHTTP2Connection._read_incoming_data, AsyncHTTP2Connection._receive_events; module: http2
**http_proxy.py** — class: AsyncForwardHTTPConnection, AsyncHTTPProxy, AsyncTunnelHTTPConnection; function: merge_headers; 23 imports; method: AsyncForwardHTTPConnection.__init__, AsyncForwardHTTPConnection.__repr__, AsyncForwardHTTPConnection.aclose, AsyncForwardHTTPConnection.can_handle_request, AsyncForwardHTTPConnection.handle_async_request, AsyncForwardHTTPConnection.has_expired; module: http_proxy
**interfaces.py** — class: AsyncConnectionInterface, AsyncRequestInterface; 13 imports; method: AsyncConnectionInterface.aclose, AsyncConnectionInterface.can_handle_request, AsyncConnectionInterface.has_expired, AsyncConnectionInterface.info, AsyncConnectionInterface.is_available, AsyncConnectionInterface.is_closed; module: interfaces
**socks_proxy.py** — class: AsyncSOCKSProxy, AsyncSocks5Connection; function: _init_socks5_connection; 22 imports; method: AsyncSOCKSProxy.__init__, AsyncSOCKSProxy.create_connection, AsyncSocks5Connection.__init__, AsyncSocks5Connection.__repr__, AsyncSocks5Connection.aclose, AsyncSocks5Connection.can_handle_request; module: socks_proxy
**anyio.py** — class: AnyIOBackend, AnyIOStream; 15 imports; method: AnyIOBackend.connect_tcp, AnyIOBackend.connect_unix_socket, AnyIOBackend.sleep, AnyIOStream.__init__, AnyIOStream.aclose, AnyIOStream.get_extra_info; module: anyio
**auto.py** — class: AutoBackend; 8 imports; method: AutoBackend._init_backend, AutoBackend.connect_tcp, AutoBackend.connect_unix_socket, AutoBackend.sleep; module: auto
**base.py** — class: AsyncNetworkBackend, AsyncNetworkStream, NetworkBackend, NetworkStream; 4 imports; method: AsyncNetworkBackend.connect_tcp, AsyncNetworkBackend.connect_unix_socket, AsyncNetworkBackend.sleep, AsyncNetworkStream.aclose, AsyncNetworkStream.get_extra_info, AsyncNetworkStream.read; module: base
**mock.py** — class: AsyncMockBackend, AsyncMockStream, MockBackend, MockSSLObject, MockStream; 9 imports; method: AsyncMockBackend.__init__, AsyncMockBackend.connect_tcp, AsyncMockBackend.connect_unix_socket, AsyncMockBackend.sleep, AsyncMockStream.__init__, AsyncMockStream.__repr__; module: mock
**sync.py** — class: SyncBackend, SyncStream, TLSinTLSStream; 18 imports; method: SyncBackend.connect_tcp, SyncBackend.connect_unix_socket, SyncStream.__init__, SyncStream.close, SyncStream.get_extra_info, SyncStream.read; module: sync
**trio.py** — class: TrioBackend, TrioStream; 15 imports; method: TrioBackend.connect_tcp, TrioBackend.connect_unix_socket, TrioBackend.sleep, TrioStream.__init__, TrioStream._get_socket_stream, TrioStream.aclose; module: trio
**_exceptions.py** — class: ConnectError, ConnectTimeout, ConnectionNotAvailable, LocalProtocolError, NetworkError, PoolTimeout; function: map_exceptions; 2 imports; module: _exceptions
**_models.py** — class: ByteStream, Origin, Proxy, Request, Response, URL; function: enforce_bytes, enforce_headers, enforce_stream, enforce_url, include_request_headers; 5 imports; method: ByteStream.__aiter__, ByteStream.__init__, ByteStream.__iter__, ByteStream.__repr__, Origin.__eq__, Origin.__init__; module: _models
**_ssl.py** — function: default_ssl_context; 2 imports; module: _ssl
**__init__.py** — 7 imports; module: __init__
**connection.py** — class: HTTPConnection; function: exponential_backoff; 21 imports; method: HTTPConnection.__enter__, HTTPConnection.__exit__, HTTPConnection.__init__, HTTPConnection.__repr__, HTTPConnection._connect, HTTPConnection.can_handle_request; module: connection
**connection_pool.py** — class: ConnectionPool, PoolByteStream, PoolRequest; 23 imports; method: ConnectionPool.__enter__, ConnectionPool.__exit__, ConnectionPool.__init__, ConnectionPool.__repr__, ConnectionPool._assign_requests_to_connections, ConnectionPool._close_connections; module: connection_pool
**http11.py** — class: HTTP11Connection, HTTP11ConnectionByteStream, HTTP11UpgradeStream, HTTPConnectionState; 21 imports; method: HTTP11Connection.__enter__, HTTP11Connection.__exit__, HTTP11Connection.__init__, HTTP11Connection.__repr__, HTTP11Connection._receive_event, HTTP11Connection._receive_response_body; module: http11
**http2.py** — class: HTTP2Connection, HTTP2ConnectionByteStream, HTTPConnectionState; function: has_body_headers; 23 imports; method: HTTP2Connection.__enter__, HTTP2Connection.__exit__, HTTP2Connection.__init__, HTTP2Connection.__repr__, HTTP2Connection._read_incoming_data, HTTP2Connection._receive_events; module: http2
**http_proxy.py** — class: ForwardHTTPConnection, HTTPProxy, TunnelHTTPConnection; function: merge_headers; 23 imports; method: ForwardHTTPConnection.__init__, ForwardHTTPConnection.__repr__, ForwardHTTPConnection.can_handle_request, ForwardHTTPConnection.close, ForwardHTTPConnection.handle_request, ForwardHTTPConnection.has_expired; module: http_proxy
**interfaces.py** — class: ConnectionInterface, RequestInterface; 13 imports; method: ConnectionInterface.can_handle_request, ConnectionInterface.close, ConnectionInterface.has_expired, ConnectionInterface.info, ConnectionInterface.is_available, ConnectionInterface.is_closed; module: interfaces
**socks_proxy.py** — class: SOCKSProxy, Socks5Connection; function: _init_socks5_connection; 22 imports; method: SOCKSProxy.__init__, SOCKSProxy.create_connection, Socks5Connection.__init__, Socks5Connection.__repr__, Socks5Connection.can_handle_request, Socks5Connection.close; module: socks_proxy
**_synchronization.py** — class: AsyncEvent, AsyncLock, AsyncSemaphore, AsyncShieldCancellation, AsyncThreadLock, Event; function: current_async_library; 9 imports; method: AsyncEvent.__init__, AsyncEvent.set, AsyncEvent.setup, AsyncEvent.wait, AsyncLock.__aenter__, AsyncLock.__aexit__; module: _synchronization
**_trace.py** — class: Trace; 6 imports; method: Trace.__aenter__, Trace.__aexit__, Trace.__enter__, Trace.__exit__, Trace.__init__, Trace.atrace; module: _trace
**_utils.py** — function: is_socket_readable; 4 imports; module: _utils; rationale: [NOTE] we want check for readability without actually attempting to read, because
**__init__.py** — 16 imports; module: __init__
**__version__.py** — module: __version__
**_api.py** — function: delete, get, head, options, patch, post; 17 imports; module: _api
**_auth.py** — class: Auth, BasicAuth, DigestAuth, FunctionAuth, NetRCAuth, _DigestAuthChallenge; 17 imports; method: Auth.async_auth_flow, Auth.auth_flow, Auth.sync_auth_flow, BasicAuth.__init__, BasicAuth._build_auth_header, BasicAuth.auth_flow; module: _auth; rationale: [TODO] implement auth-int
**_client.py** — class: AsyncClient, BaseClient, BoundAsyncStream, BoundSyncStream, Client, ClientState; function: _is_https_redirect, _port_or_default, _same_origin; 53 imports; method: AsyncClient.__aenter__, AsyncClient.__aexit__, AsyncClient.__init__, AsyncClient._init_proxy_transport, AsyncClient._init_transport, AsyncClient._send_handling_auth; module: _client
**_config.py** — class: Limits, Proxy, Timeout, UnsetType; function: create_ssl_context; 11 imports; method: Limits.__eq__, Limits.__init__, Limits.__repr__, Proxy.__init__, Proxy.__repr__, Proxy.raw_auth; module: _config
**_content.py** — class: AsyncIteratorByteStream, ByteStream, IteratorByteStream, UnattachedStream; function: encode_content, encode_html, encode_json, encode_multipart_data, encode_request, encode_response; 22 imports; method: AsyncIteratorByteStream.__aiter__, AsyncIteratorByteStream.__init__, ByteStream.__aiter__, ByteStream.__init__, ByteStream.__iter__, IteratorByteStream.__init__; module: _content
**_decoders.py** — class: BrotliDecoder, ByteChunker, ContentDecoder, DeflateDecoder, GZipDecoder, IdentityDecoder; 9 imports; method: BrotliDecoder.__init__, BrotliDecoder.decode, BrotliDecoder.flush, ByteChunker.__init__, ByteChunker.decode, ByteChunker.flush; module: _decoders; rationale: [NOTE] the edge case input of empty text doesn't occur in practice,, [NOTE] this is a no-op
**_exceptions.py** — class: CloseError, ConnectError, ConnectTimeout, CookieConflict, DecodingError, HTTPError; function: request_context; 5 imports; method: CookieConflict.__init__, HTTPError.__init__, HTTPError.request, HTTPStatusError.__init__, InvalidURL.__init__, RequestError.__init__; module: _exceptions
**_main.py** — function: download_response, format_certificate, format_request_headers, format_response_headers, get_lexer_for_response, handle_help; 18 imports; module: _main
**_models.py** — class: Cookies, Headers, Request, Response; function: _is_known_encoding, _normalize_header_key, _normalize_header_value, _obfuscate_sensitive_headers, _parse_content_type_charset, _parse_header_links; 46 imports; method: Cookies.__bool__, Cookies.__delitem__, Cookies.__getitem__, Cookies.__init__, Cookies.__iter__, Cookies.__len__; module: _models
**_multipart.py** — class: DataField, FileField, MultipartStream; function: _format_form_param, _guess_content_type, get_multipart_boundary_from_content_type; 16 imports; method: DataField.__init__, DataField.get_length, DataField.render, DataField.render_data, DataField.render_headers, FileField.__init__; module: _multipart
**_status_codes.py** — class: codes; 2 imports; method: codes.__new__, codes.__str__, codes.get_reason_phrase, codes.is_client_error, codes.is_error, codes.is_informational; module: _status_codes
**__init__.py** — 5 imports; module: __init__
**asgi.py** — class: ASGIResponseStream, ASGITransport; function: create_event, is_running_trio; 9 imports; method: ASGIResponseStream.__aiter__, ASGIResponseStream.__init__, ASGITransport.__init__, ASGITransport.handle_async_request; module: asgi
**base.py** — class: AsyncBaseTransport, BaseTransport; 5 imports; method: AsyncBaseTransport.__aenter__, AsyncBaseTransport.__aexit__, AsyncBaseTransport.aclose, AsyncBaseTransport.handle_async_request, BaseTransport.__enter__, BaseTransport.__exit__; module: base
**default.py** — class: AsyncHTTPTransport, AsyncResponseStream, HTTPTransport, ResponseStream; function: _load_httpcore_exceptions, map_httpcore_exceptions; 35 imports; method: AsyncHTTPTransport.__aenter__, AsyncHTTPTransport.__aexit__, AsyncHTTPTransport.__init__, AsyncHTTPTransport.aclose, AsyncHTTPTransport.handle_async_request, AsyncResponseStream.__aiter__; module: default
**mock.py** — class: MockTransport; 6 imports; method: MockTransport.__init__, MockTransport.handle_async_request, MockTransport.handle_request; module: mock
**wsgi.py** — class: WSGIByteStream, WSGITransport; function: _skip_leading_empty_chunks; 11 imports; method: WSGIByteStream.__init__, WSGIByteStream.__iter__, WSGIByteStream.close, WSGITransport.__init__, WSGITransport.handle_request; module: wsgi
**_types.py** — class: AsyncByteStream, SyncByteStream; 24 imports; method: AsyncByteStream.__aiter__, AsyncByteStream.aclose, SyncByteStream.__iter__, SyncByteStream.close; module: _types
**_urlparse.py** — class: ParseResult; function: PERCENT, encode_host, normalize_path, normalize_port, percent_encoded, quote; 6 imports; method: ParseResult.__str__, ParseResult.authority, ParseResult.copy_with, ParseResult.netloc; module: _urlparse
**_urls.py** — class: QueryParams, URL; 12 imports; method: QueryParams.__bool__, QueryParams.__contains__, QueryParams.__eq__, QueryParams.__getitem__, QueryParams.__hash__, QueryParams.__init__; module: _urls
**_utils.py** — class: URLPattern; function: get_environment_proxies, is_ipv4_hostname, is_ipv6_hostname, peek_filelike_length, primitive_value_to_str, to_bytes; 8 imports; method: URLPattern.__eq__, URLPattern.__hash__, URLPattern.__init__, URLPattern.__lt__, URLPattern.matches, URLPattern.priority; module: _utils
**__init__.py** — 5 imports; module: __init__
**_api.py** — class: EventSource; function: _aiter_sse_lines, _iter_sse_lines, aconnect_sse, connect_sse; 12 imports; method: EventSource.__init__, EventSource._check_content_type, EventSource.aiter_sse, EventSource.iter_sse, EventSource.response; module: _api
**_decoders.py** — class: SSEDecoder, SSELineDecoder; function: _splitlines_sse; 3 imports; method: SSEDecoder.__init__, SSEDecoder.decode, SSELineDecoder.__init__, SSELineDecoder.decode, SSELineDecoder.flush; module: _decoders; rationale: [NOTE] as per the SSE spec, do not reset last_event_id., [NOTE] the edge case input of empty text doesn't occur in practice,
**_exceptions.py** — class: SSEError; 1 imports; module: _exceptions
**_models.py** — class: ServerSentEvent; 3 imports; method: ServerSentEvent.__init__, ServerSentEvent.__repr__, ServerSentEvent.data, ServerSentEvent.event, ServerSentEvent.id, ServerSentEvent.json; module: _models
**__init__.py** — 20 imports; module: __init__
**__main__.py** — 2 imports; module: __main__
**cli.py** — function: _build_parser, _convert_one, _iter_stdin, _looks_like_alabel, main; 12 imports; module: cli
**codec.py** — class: Codec, IncrementalDecoder, IncrementalEncoder, StreamReader, StreamWriter; function: search_function; 9 imports; method: Codec.decode, Codec.encode, IncrementalDecoder._buffer_decode, IncrementalEncoder._buffer_encode; module: codec
**compat.py** — function: ToASCII, ToUnicode, nameprep; 4 imports; module: compat
**core.py** — class: IDNABidiError, IDNAError, InvalidCodepoint, InvalidCodepointContext; function: _combining_class, _is_script, _joining_type, _punycode, _unot, alabel; 11 imports; module: core
**idnadata.py** — module: idnadata
**intranges.py** — function: _decode_range, _encode_range, intranges_contain, intranges_from_list; 1 imports; module: intranges
**package_data.py** — module: package_data
**uts46data.py** — 2 imports; module: uts46data
**__init__.py** — class: Graph; function: get_include, read, write; 215 imports; method: Graph.Incidence, Graph.__bool__, Graph.__coerce__, Graph.__init__, Graph.__reduce__, Graph.__str__; module: __init__
**adjacency.py** — function: _get_adjacency, _get_adjacency_sparse, _get_adjlist, _get_biadjacency, _get_inclist; 7 imports; module: adjacency
**__init__.py** — module: __init__
**shell.py** — class: ClassicPythonShell, ConsoleProgressBarMixin, IDLEShell, IPythonShell, ProgressBar, Shell; function: main; 16 imports; method: ClassicPythonShell.__call__, ClassicPythonShell.__init__, ConsoleProgressBarMixin.__init__, ConsoleProgressBarMixin._disable_handlers, ConsoleProgressBarMixin._progress_handler, ConsoleProgressBarMixin._status_handler; module: shell; rationale: [TODO] no progress bar support yet. Shell/Restart Shell command should
**automorphisms.py** — function: _count_automorphisms_vf2, _get_automorphisms_vf2; module: automorphisms
**basic.py** — function: _add_edge, _add_edges, _add_vertex, _add_vertices, _as_directed, _as_undirected; 3 imports; module: basic
**bipartite.py** — function: _bipartite_projection, _bipartite_projection_size, _maximum_bipartite_matching; 3 imports; module: bipartite
**clustering.py** — class: Clustering, CohesiveBlocks, Cover, Dendrogram, VertexClustering, VertexCover; function: _biconnected_components, _clusters, _cohesive_blocks, _connected_components, _handle_mark_groups_arg_for_clustering, _prepare_community_comparison; 18 imports; method: Clustering.__getitem__, Clustering.__init__, Clustering.__iter__, Clustering.__len__, Clustering.__str__, Clustering._formatted_cluster_iterator; module: clustering
**community.py** — function: _community_edge_betweenness, _community_fastgreedy, _community_fluid_communities, _community_infomap, _community_label_propagation, _community_leading_eigenvector; 8 imports; module: community
**configuration.py** — class: Configuration; function: get_user_config_file, init; 7 imports; method: Configuration.__contains__, Configuration.__delitem__, Configuration.__getitem__, Configuration.__init__, Configuration.__setitem__, Configuration._get; module: configuration
**cut.py** — class: Cut, Flow; function: _all_st_cuts, _all_st_mincuts, _gomory_hu_tree, _maxflow, _mincut, _st_mincut; 2 imports; method: Cut.__init__, Cut.__repr__, Cut.__str__, Cut.cut, Cut.es, Cut.partition; module: cut
**datatypes.py** — class: DyadCensus, Matrix, TriadCensus, UniqueIdGenerator; 2 imports; method: DyadCensus.__getattr__, DyadCensus.__getitem__, DyadCensus.__repr__, DyadCensus.__str__, DyadCensus.as_dict, Matrix.Fill; module: datatypes
**__init__.py** — class: DrawerDirectory; function: plot; 22 imports; method: DrawerDirectory.resolve; module: __init__; rationale: [TODO] deprecate, [TODO] deprecate
**baseclasses.py** — class: AbstractDrawer, AbstractEdgeDrawer, AbstractGraphDrawer, AbstractVertexDrawer, AbstractXMLRPCDrawer; 13 imports; method: AbstractDrawer.draw, AbstractEdgeDrawer._curvature_to_float, AbstractEdgeDrawer.draw_directed_edge, AbstractEdgeDrawer.draw_undirected_edge, AbstractEdgeDrawer.get_label_position, AbstractEdgeDrawer.get_label_rotation; module: baseclasses; rationale: [TODO] curved edges don't play terribly well with this function,
**__init__.py** — 1 imports; module: __init__
**base.py** — class: AbstractCairoDrawer; 5 imports; method: AbstractCairoDrawer.__init__, AbstractCairoDrawer._mark_point, AbstractCairoDrawer.bbox; module: base
**coord.py** — class: CoordinateSystem, DescartesCoordinateSystem; 3 imports; method: CoordinateSystem.draw, CoordinateSystem.local_to_context, DescartesCoordinateSystem.__init__, DescartesCoordinateSystem._recalc_scale_factors, DescartesCoordinateSystem.bbox, DescartesCoordinateSystem.bounds; module: coord
**dendrogram.py** — class: CairoDendrogramDrawer; 4 imports; method: CairoDendrogramDrawer.__init__, CairoDendrogramDrawer._item_box_size, CairoDendrogramDrawer._plot_item, CairoDendrogramDrawer.draw; module: dendrogram
**edge.py** — class: AbstractCairoEdgeDrawer, AlphaVaryingEdgeDrawer, CairoArrowEdgeDrawer, DarkToLightEdgeDrawer, LightToDarkEdgeDrawer, TaperedEdgeDrawer; 11 imports; method: AbstractCairoEdgeDrawer.__init__, AbstractCairoEdgeDrawer._construct_visual_edge_builder, AbstractCairoEdgeDrawer.draw_loop_edge, AbstractCairoEdgeDrawer.draw_undirected_edge, AlphaVaryingEdgeDrawer.__init__, AlphaVaryingEdgeDrawer.draw_directed_edge; module: edge
**graph.py** — class: AbstractCairoGraphDrawer, CairoGraphDrawer; 21 imports; method: AbstractCairoGraphDrawer.__init__, CairoGraphDrawer.__init__, CairoGraphDrawer.draw; module: graph
**histogram.py** — class: CairoHistogramDrawer; 2 imports; method: CairoHistogramDrawer.__init__, CairoHistogramDrawer.draw; module: histogram
**matrix.py** — class: CairoMatrixDrawer; 3 imports; method: CairoMatrixDrawer.__init__, CairoMatrixDrawer.draw; module: matrix
**palette.py** — class: CairoPaletteDrawer; 3 imports; method: CairoPaletteDrawer.__init__, CairoPaletteDrawer.draw; module: palette
**plot.py** — class: CairoPlot; 9 imports; method: CairoPlot.__init__, CairoPlot._repr_svg_, CairoPlot.add, CairoPlot.background, CairoPlot.bounding_box, CairoPlot.height; module: plot
**polygon.py** — class: CairoPolygonDrawer; 3 imports; method: CairoPolygonDrawer.__init__, CairoPolygonDrawer.draw, CairoPolygonDrawer.draw_path; module: polygon
**text.py** — class: CairoTextDrawer; function: test; 6 imports; method: CairoTextDrawer.__init__, CairoTextDrawer._iterlines, CairoTextDrawer._iterlines_wrapped, CairoTextDrawer.draw, CairoTextDrawer.draw_at, CairoTextDrawer.get_text_layout; module: text
**utils.py** — function: find_cairo; 2 imports; module: utils
**vertex.py** — class: AbstractCairoVertexDrawer, CairoVertexDrawer; 5 imports; method: AbstractCairoVertexDrawer.__init__, CairoVertexDrawer.__init__, CairoVertexDrawer._construct_visual_vertex_builder, CairoVertexDrawer.draw; module: vertex
**colors.py** — class: AdvancedGradientPalette, ClusterColoringPalette, GradientPalette, Palette, PrecalculatedPalette, RainbowPalette; function: clamp, color_name_to_rgb, color_name_to_rgba, color_to_html_format, darken, hsl_to_rgb; 4 imports; method: AdvancedGradientPalette.__init__, AdvancedGradientPalette._get, ClusterColoringPalette.__init__, GradientPalette.__init__, GradientPalette._get, Palette.__init__; module: colors
**graph.py** — class: CytoscapeGraphDrawer, GephiGraphStreamingDrawer; function: __plot__; 8 imports; method: CytoscapeGraphDrawer.__init__, CytoscapeGraphDrawer.draw, CytoscapeGraphDrawer.fetch, CytoscapeGraphDrawer.infer_cytoscape_type, GephiGraphStreamingDrawer.__init__, GephiGraphStreamingDrawer.draw; module: graph
**dendrogram.py** — class: MatplotlibDendrogramDrawer; 4 imports; method: MatplotlibDendrogramDrawer.__init__, MatplotlibDendrogramDrawer._plot_item, MatplotlibDendrogramDrawer.draw; module: dendrogram; rationale: [TODO] offset a little? But remember zoom in callbacks, [TODO] this is a little restrictive, but alright, [TODO] this is a little restrictive, but alright
**edge.py** — class: EdgeCollection, MatplotlibEdgeDrawer; 10 imports; method: EdgeCollection.__init__, EdgeCollection._compute_edge_angles, EdgeCollection._compute_path_directed, EdgeCollection._compute_path_loop, EdgeCollection._compute_path_undirected, EdgeCollection._compute_paths; module: edge
**graph.py** — class: GraphArtist, MatplotlibGraphDrawer; function: _additional_set_methods, _forwarder, _stale_wrapper; 17 imports; method: GraphArtist.__init__, GraphArtist._clear_state, GraphArtist._draw_edge_labels, GraphArtist._draw_edges, GraphArtist._draw_groups, GraphArtist._draw_vertex_labels; module: graph; rationale: [NOTE] https://github.com/networkx/grave/blob/main/grave/grave.py, [NOTE] looks like we have to manage the zorder ourselves, [NOTE] no need to reprocess here because it does not affect other, [NOTE] unlike other Collections, the vertices are basically a
**histogram.py** — class: MatplotlibHistogramDrawer; 1 imports; method: MatplotlibHistogramDrawer.__init__, MatplotlibHistogramDrawer.draw; module: histogram
**matrix.py** — class: MatplotlibMatrixDrawer; 1 imports; method: MatplotlibMatrixDrawer.__init__, MatplotlibMatrixDrawer.draw; module: matrix
**palette.py** — class: MatplotlibPaletteDrawer; 4 imports; method: MatplotlibPaletteDrawer.__init__, MatplotlibPaletteDrawer.draw; module: palette
**polygon.py** — class: HullCollection; 6 imports; method: HullCollection.__init__, HullCollection._compute_path_with_corner_radius, HullCollection._expand_path, HullCollection._round_corners, HullCollection._update_paths, HullCollection.draw; module: polygon
**utils.py** — function: find_matplotlib; 4 imports; module: utils
**vertex.py** — class: MatplotlibVertexDrawer, VertexCollection; 7 imports; method: MatplotlibVertexDrawer.__init__, MatplotlibVertexDrawer._construct_visual_vertex_builder, MatplotlibVertexDrawer.draw, VertexCollection.__init__, VertexCollection.get_size, VertexCollection.get_sizes; module: vertex
**metamagic.py** — class: AttributeCollectorBase, AttributeCollectorMeta, AttributeSpecification; 2 imports; method: AttributeCollectorBase.__getitem__, AttributeCollectorBase.__init__, AttributeCollectorBase.__len__, AttributeCollectorBase._collect_attributes, AttributeCollectorMeta.__new__, AttributeCollectorMeta.record_generator; module: metamagic
**edge.py** — class: PlotlyEdgeDrawer; 14 imports; method: PlotlyEdgeDrawer.__init__, PlotlyEdgeDrawer._construct_visual_edge_builder, PlotlyEdgeDrawer.draw_directed_edge, PlotlyEdgeDrawer.draw_loop_edge, PlotlyEdgeDrawer.draw_undirected_edge; module: edge; rationale: [FIXME] this is tricky in plotly, let's skip for now
**graph.py** — class: PlotlyGraphDrawer; 13 imports; method: PlotlyGraphDrawer.__init__, PlotlyGraphDrawer.draw; module: graph; rationale: [FIXME] colors do not work yet; apparently we need to convert, [FIXME] horizontal/vertical alignment, offset, etc?
**polygon.py** — class: PlotlyPolygonDrawer; 4 imports; method: PlotlyPolygonDrawer.__init__, PlotlyPolygonDrawer.draw; module: polygon
**utils.py** — function: find_plotly, format_arc, format_path_step, format_rgba; 4 imports; module: utils
**vertex.py** — class: PlotlyVerticesDrawer; 5 imports; method: PlotlyVerticesDrawer.__init__, PlotlyVerticesDrawer._construct_visual_vertex_builder, PlotlyVerticesDrawer.draw, PlotlyVerticesDrawer.draw_label; module: vertex; rationale: [TODO] add more options
**shapes.py** — class: CircleDrawer, DiamondDrawer, DownTriangleDrawer, NullDrawer, RectangleDrawer, ShapeDrawer; 9 imports; method: CircleDrawer.draw_path, CircleDrawer.intersection_point, DiamondDrawer.draw_path, DiamondDrawer.intersection_point, DownTriangleDrawer.draw_path, DownTriangleDrawer.intersection_point; module: shapes; rationale: [TODO] finish it properly, [TODO] finish it properly
**text.py** — class: TextAlignment; 1 imports; module: text
**utils.py** — class: BoundingBox, FakeModule, Point, Rectangle; function: autocurve, calculate_corner_radii, euclidean_distance, evaluate_cubic_bezier, get_bezier_control_points_for_curved_edge, intersect_bezier_curve_and_circle; 7 imports; method: BoundingBox.__ior__, BoundingBox.__or__, FakeModule.__call__, FakeModule.__getattr__, FakeModule.__init__, FakeModule.__setattr__; module: utils
**formula.py** — function: construct_graph_from_formula, generate_edges; 5 imports; module: formula
**__init__.py** — module: __init__
**adjacency.py** — function: _construct_graph_from_adjacency, _construct_graph_from_weighted_adjacency; 6 imports; module: adjacency
**bipartite.py** — function: _construct_bipartite_graph, _construct_bipartite_graph_from_adjacency, _construct_full_bipartite_graph, _construct_random_bipartite_graph; module: bipartite
**files.py** — function: _construct_graph_from_adjacency_file, _construct_graph_from_dimacs_file, _construct_graph_from_file, _construct_graph_from_graphmlz_file, _construct_graph_from_pickle_file, _construct_graph_from_picklez_file; 9 imports; module: files
**images.py** — function: _write_graph_to_svg; 4 imports; module: images
**libraries.py** — function: _construct_graph_from_graph_tool, _construct_graph_from_networkx, _export_graph_to_graph_tool, _export_graph_to_networkx; 2 imports; module: libraries; rationale: [NOTE] graph-tool is quite strongly typed, so each property is always, [NOTE] we do not need a special class for multigraphs, it is taken
**objects.py** — function: _construct_graph_from_dataframe, _construct_graph_from_dict_dict, _construct_graph_from_dict_list, _construct_graph_from_list_dict, _construct_graph_from_tuple_list, _export_edge_dataframe; 7 imports; module: objects
**random.py** — function: _construct_random_geometric_graph; module: random
**utils.py** — function: safe_locale; 4 imports; module: utils
**layout.py** — class: Layout; function: _3d_version_for, _layout, _layout_auto, _layout_method_wrapper, _layout_sugiyama, align_layout; 8 imports; method: Layout.__copy__, Layout.__delitem__, Layout.__getitem__, Layout.__init__, Layout.__len__, Layout.__repr__; module: layout
**matching.py** — class: Matching; 1 imports; method: Matching.__init__, Matching.__len__, Matching.__repr__, Matching.__str__, Matching.edges, Matching.graph; module: matching
**__init__.py** — 13 imports; module: __init__
**functions.py** — function: disjoint_union, intersection, name_set, union; 5 imports; module: functions; rationale: [NOTE] a_first_graph tracks which graph has the 1st occurrence of an, [NOTE] a_name is the name of the attribute, a_value its value, [NOTE] a_name is the name of the attribute, a_value its value, [NOTE] a_name is the name of the attribute, a_value its value
**methods.py** — function: __add__, __and__, __iadd__, __isub__, __mul__, __or__; 9 imports; module: methods
**__init__.py** — module: __init__
**gephi.py** — class: GephiConnection, GephiGraphStreamer, GephiGraphStreamingAPIFormat; 4 imports; method: GephiConnection.__del__, GephiConnection.__init__, GephiConnection.__repr__, GephiConnection._construct_default_url, GephiConnection.close, GephiConnection.flush; module: gephi
**rewiring.py** — function: _rewire; 2 imports; module: rewiring
**seq.py** — class: EdgeSeq, VertexSeq; function: _add_proxy_methods, _graphmethod; 4 imports; method: EdgeSeq.__call__, EdgeSeq.attributes, EdgeSeq.find, EdgeSeq.select, VertexSeq.__call__, VertexSeq.attributes; module: seq
**sparse_matrix.py** — function: _convert_mode_argument, _graph_from_sparse_matrix, _graph_from_weighted_sparse_matrix, _maybe_halve_diagonal; 10 imports; module: sparse_matrix
**statistics.py** — class: FittedPowerLaw, Histogram, RunningMean; function: mean, median, percentile, power_law_fit, quantile, sd; 3 imports; method: FittedPowerLaw.__init__, FittedPowerLaw.__repr__, FittedPowerLaw.__str__, FittedPowerLaw.summary, Histogram.__init__, Histogram.__plot__; module: statistics
**structural.py** — function: _degree_distribution, _indegree, _outdegree, _pagerank, _shortest_paths; 5 imports; module: structural
**summary.py** — class: FakeWrapper, GraphSummary; function: _get_wrapper_for_width, summary; 6 imports; method: FakeWrapper.__init__, FakeWrapper.fill, FakeWrapper.wrap, GraphSummary.__init__, GraphSummary.__str__, GraphSummary._construct_edgelist_adjlist; module: summary
**utils.py** — class: multidict; function: _is_running_in_ipython, consecutive_pairs, dbl_epsilon, deprecated, named_temporary_file, numpy_to_contiguous_memoryview; 11 imports; method: multidict.__contains__, multidict.__delitem__, multidict.__getitem__, multidict.__init__, multidict.__iter__, multidict.__len__; module: utils
**version.py** — module: version
**__init__.py** — class: ExtensionError, FilterError, ISAPIError, InternalReloadException; 1 imports; method: ISAPIError.__init__, ISAPIError.__str__; module: __init__
**install.py** — class: ConfigurationError, FilterParameters, ISAPIParameters, InstallationError, ItemNotFound, ScriptMapParams; function: AddExtensionFiles, AssignScriptMaps, CheckLoaderModule, CreateDirectory, CreateISAPIFilter, DeleteExtensionFileRecords; 13 imports; method: FilterParameters.__init__, ISAPIParameters.__init__, ScriptMapParams.__init__, ScriptMapParams.__str__, VirtualDirParameters.__init__, VirtualDirParameters.is_root; module: install
**isapicon.py** — module: isapicon
**advanced.py** — class: Extension, ReloadWatcherThread; function: PostInstall, PreInstallDirectory, __ExtensionFactory__, status_handler; 14 imports; method: Extension.HttpExtensionProc, Extension.TerminateExtension, Extension.__init__, ReloadWatcherThread.__init__, ReloadWatcherThread.run, ReloadWatcherThread.stop; module: advanced; rationale: [NOTE] If you use a ThreadPoolExtension, you must still perform
**redirector.py** — class: Extension; function: __ExtensionFactory__, io_callback; 7 imports; method: Extension.Dispatch; module: redirector
**redirector_asynch.py** — class: Extension; function: __ExtensionFactory__, io_callback; 8 imports; method: Extension.Dispatch; module: redirector_asynch
**redirector_with_filter.py** — class: Extension, Filter; function: __ExtensionFactory__, __FilterFactory__; 9 imports; method: Extension.Dispatch, Filter.HttpFilterProc; module: redirector_with_filter
**test.py** — class: Extension, ReloadWatcherThread; function: PostInstall, PreInstallDirectory, TransmitFileCallback, __ExtensionFactory__, status_handler; 14 imports; method: Extension.HttpExtensionProc, Extension.TerminateExtension, Extension.__init__, ReloadWatcherThread.__init__, ReloadWatcherThread.run, ReloadWatcherThread.stop; module: test; rationale: [NOTE] If you use a ThreadPoolExtension, you must still perform
**simple.py** — class: SimpleExtension, SimpleFilter; 1 imports; method: SimpleExtension.GetExtensionVersion, SimpleExtension.HttpExtensionProc, SimpleExtension.TerminateExtension, SimpleExtension.__init__, SimpleFilter.GetFilterVersion, SimpleFilter.HttpFilterProc; module: simple
**extension_simple.py** — class: Extension; function: __ExtensionFactory__; 6 imports; method: Extension.Dispatch, Extension.test1, Extension.test_long_vars, Extension.test_unicode_vars; module: extension_simple
**threaded_extension.py** — class: ThreadPoolExtension, WorkerThread; 15 imports; method: ThreadPoolExtension.Dispatch, ThreadPoolExtension.DispatchConnection, ThreadPoolExtension.GetExtensionVersion, ThreadPoolExtension.HandleDispatchError, ThreadPoolExtension.HttpExtensionProc, ThreadPoolExtension.TerminateExtension; module: threaded_extension
**__init__.py** — function: __getattr__; 18 imports; module: __init__
**__main__.py** — 1 imports; module: __main__
**_format.py** — class: FormatChecker; function: _checks_drafts, is_date, is_draft3_time, is_email, is_ipv4, is_ipv6; 20 imports; method: FormatChecker.__init__, FormatChecker.__repr__, FormatChecker._cls_checks, FormatChecker.check, FormatChecker.checks, FormatChecker.cls_checks; module: _format; rationale: [FIXME] See bolsote/isoduration#25 and bolsote/isoduration#21, [TODO] I don't want to maintain this, so it
**_keywords.py** — function: additionalProperties, allOf, anyOf, const, contains, dependentRequired; 11 imports; module: _keywords; rationale: [FIXME] Include context for each unevaluated property
**_legacy_keywords.py** — function: additionalItems, contains_draft6_draft7, dependencies_draft3, dependencies_draft4_draft6_draft7, disallow_draft3, extends_draft3; 4 imports; module: _legacy_keywords; rationale: [FIXME] Include context for each unevaluated property
**_types.py** — class: TypeChecker; function: _typed_map_converter, is_any, is_array, is_bool, is_integer, is_null; 11 imports; method: TypeChecker.__repr__, TypeChecker.is_type, TypeChecker.redefine, TypeChecker.redefine_many, TypeChecker.remove; module: _types
**_typing.py** — class: SchemaKeywordValidator; 6 imports; method: SchemaKeywordValidator.__call__; module: _typing
**_utils.py** — class: URIDict, Unset; function: _mapping_equal, _sequence_equal, ensure_list, equal, extras_msg, find_additional_properties; 6 imports; method: URIDict.__delitem__, URIDict.__getitem__, URIDict.__init__, URIDict.__iter__, URIDict.__len__, URIDict.__repr__; module: _utils
**__init__.py** — module: __init__
**const_vs_enum.py** — 2 imports; module: const_vs_enum
**contains.py** — 2 imports; module: contains
**import_benchmark.py** — function: import_time; 3 imports; module: import_benchmark
**issue232.py** — 5 imports; module: issue232
**json_schema_test_suite.py** — 2 imports; module: json_schema_test_suite
**nested_schemas.py** — function: nested_schema; 3 imports; module: nested_schemas
**subcomponents.py** — function: registry_add, registry_data_structures; 6 imports; module: subcomponents
**unused_registry.py** — 4 imports; module: unused_registry
**useless_applicator_schemas.py** — 2 imports; module: useless_applicator_schemas
**useless_keywords.py** — 2 imports; module: useless_keywords
**validator_creation.py** — 2 imports; module: validator_creation
**cli.py** — class: _CannotLoadFile, _Outputter, _PlainFormatter, _PrettyFormatter; function: _resolve_name_with_default, _validate_instance, main, parse_args, run; 14 imports; method: _Outputter.filenotfound_error, _Outputter.from_arguments, _Outputter.load, _Outputter.parsing_error, _Outputter.validation_error, _Outputter.validation_success; module: cli
**exceptions.py** — class: ErrorTree, FormatError, SchemaError, UndefinedTypeCheck, UnknownType, ValidationError; function: __getattr__, _pretty, best_match, by_relevance; 20 imports; method: ErrorTree.__contains__, ErrorTree.__getitem__, ErrorTree.__init__, ErrorTree.__iter__, ErrorTree.__len__, ErrorTree.__repr__; module: exceptions
**protocols.py** — class: Validator; 13 imports; method: Validator.__init__, Validator.check_schema, Validator.evolve, Validator.is_type, Validator.is_valid, Validator.iter_errors; module: protocols
**_suite.py** — class: Suite, Version, _Case, _Test; function: _find_suite, _someone_save_us_the_module_of_the_caller, remotes_in; 22 imports; method: Suite.benchmark, Suite.version, Version._cases_in, Version.benchmark, Version.cases, Version.format_cases; module: _suite
**fuzz_validate.py** — function: main, test_schemas; 5 imports; module: fuzz_validate
**test_cli.py** — class: TestCLI, TestCLIIntegration, TestParser; function: _message_for, fake_open, fake_validator; 22 imports; method: TestCLI.assertOutputs, TestCLI.run_cli, TestCLI.test_custom_error_format, TestCLI.test_custom_error_format_applies_to_schema_errors, TestCLI.test_instance_does_not_exist, TestCLI.test_instance_does_not_exist_pretty_output; module: test_cli
**test_deprecations.py** — class: TestDeprecations; 31 imports; method: TestDeprecations.test_ErrorTree_setitem, TestDeprecations.test_FormatChecker_cls_checks, TestDeprecations.test_RefResolutionError, TestDeprecations.test_RefResolver, TestDeprecations.test_RefResolver_in_scope, TestDeprecations.test_Validator_is_valid_two_arguments; module: test_deprecations
**test_exceptions.py** — class: TestBestMatch, TestByRelevance, TestErrorInitReprStr, TestErrorTree, TestHashable, TestJsonPathRendering; 5 imports; method: TestBestMatch.best_match_of, TestBestMatch.test_anyOf_traversal_for_non_type_matching_sibling_errors, TestBestMatch.test_anyOf_traversal_for_single_equally_relevant_error, TestBestMatch.test_anyOf_traversal_for_single_sibling_errors, TestBestMatch.test_boolean_schemas, TestBestMatch.test_if_the_most_relevant_error_is_allOf_it_is_traversed; module: test_exceptions; rationale: [FIXME] #442
**test_format.py** — class: TestFormatChecker; function: boom; 5 imports; method: TestFormatChecker.test_format_checkers_come_with_defaults, TestFormatChecker.test_format_error_causes_become_validation_error_causes, TestFormatChecker.test_it_can_register_checkers, TestFormatChecker.test_it_can_register_cls_checkers, TestFormatChecker.test_it_can_validate_no_formats, TestFormatChecker.test_it_catches_registered_errors; module: test_format
**test_jsonschema_test_suite.py** — function: complex_email_validation, ecmascript_regex, leap_second, missing_format, skip; 2 imports; module: test_jsonschema_test_suite
**test_types.py** — class: TestCustomTypes, TestTypeChecker; function: equals_2, is_namedtuple, is_object_or_named_tuple; 9 imports; method: TestCustomTypes.test_object_can_be_extended, TestCustomTypes.test_object_extensions_can_handle_custom_validators, TestCustomTypes.test_object_extensions_require_custom_validators, TestCustomTypes.test_simple_type_can_be_extended, TestCustomTypes.test_unknown_type, TestTypeChecker.test_checks_can_be_added_at_init; module: test_types
**test_utils.py** — class: TestDictEqual, TestEqual, TestListEqual; 3 imports; method: TestDictEqual.test_additional_key, TestDictEqual.test_empty_dictionaries, TestDictEqual.test_equal_dictionaries, TestDictEqual.test_equal_dictionaries_with_nan, TestDictEqual.test_missing_key, TestDictEqual.test_missing_value; module: test_utils
**test_validators.py** — class: AntiDraft6LeakMixin, MetaSchemaTestsMixin, ReallyFakeRequests, TestCreateAndExtend, TestDraft201909Validator, TestDraft202012Validator; function: fail, sorted_errors; 25 imports; method: AntiDraft6LeakMixin.test_False_is_not_a_schema, AntiDraft6LeakMixin.test_False_is_not_a_schema_even_if_you_forget_to_check, AntiDraft6LeakMixin.test_True_is_not_a_schema, AntiDraft6LeakMixin.test_True_is_not_a_schema_even_if_you_forget_to_check, MetaSchemaTestsMixin.test_enum_allows_empty_arrays, MetaSchemaTestsMixin.test_enum_allows_non_unique_items; module: test_validators; rationale: [TODO] These all belong upstream, [TODO] These really need unit tests for each individual keyword, rather
**test_all_concrete_validators_match_protocol.py** — 7 imports; module: test_all_concrete_validators_match_protocol
**validators.py** — class: _RefResolver; function: __getattr__, _match_keyword, _match_subschema_keywords, _search_schema, _warn_for_remote_retrieve, create; 36 imports; method: _RefResolver.__init__, _RefResolver._find_in_referrer, _RefResolver._find_in_subschemas, _RefResolver._get_subschemas_cache, _RefResolver.base_uri, _RefResolver.from_schema; module: validators; rationale: [TODO] include new meta-schemas added at runtime
**__init__.py** — 2 imports; module: __init__
**_core.py** — function: _schemas; 4 imports; module: _core
**test_jsonschema_specifications.py** — function: test_it_contains_metaschemas, test_it_copes_with_dotfiles, test_it_is_crawled; 5 imports; module: test_jsonschema_specifications
**__init__.py** — 29 imports; module: __init__
**algorithms.py** — class: Algorithm, HMACAlgorithm, NoneAlgorithm; function: get_default_algorithms; 69 imports; method: Algorithm.check_crypto_key_type, Algorithm.check_key_length, Algorithm.compute_hash_digest, Algorithm.from_jwk, Algorithm.prepare_key, Algorithm.sign; module: algorithms
**api_jwk.py** — class: PyJWK, PyJWKSet, PyJWTSetWithTimestamp; 14 imports; method: PyJWK.__init__, PyJWK.from_dict, PyJWK.from_json, PyJWK.key_id, PyJWK.key_type, PyJWK.public_key_use; module: api_jwk
**api_jws.py** — class: PyJWS; 24 imports; method: PyJWS.__init__, PyJWS._get_default_options, PyJWS._load, PyJWS._validate_crit, PyJWS._validate_headers, PyJWS._validate_kid; module: api_jws
**api_jwt.py** — class: PyJWT; 37 imports; method: PyJWT.__init__, PyJWT._decode_payload, PyJWT._encode_payload, PyJWT._get_default_options, PyJWT._get_sig_options, PyJWT._merge_options; module: api_jwt
**exceptions.py** — class: DecodeError, ExpiredSignatureError, ImmatureSignatureError, InvalidAlgorithmError, InvalidAudienceError, InvalidIssuedAtError; method: MissingRequiredClaimError.__init__, MissingRequiredClaimError.__str__; module: exceptions
**help.py** — function: info, main; 5 imports; module: help
**jwk_set_cache.py** — class: JWKSetCache; 4 imports; method: JWKSetCache.__init__, JWKSetCache.get, JWKSetCache.is_expired, JWKSetCache.put; module: jwk_set_cache
**jwks_client.py** — class: PyJWKClient; 15 imports; method: PyJWKClient.__init__, PyJWKClient.fetch_data, PyJWKClient.get_jwk_set, PyJWKClient.get_signing_key, PyJWKClient.get_signing_key_from_jwt, PyJWKClient.get_signing_keys; module: jwks_client
**types.py** — class: FullOptions, Options, SigOptions; 3 imports; module: types
**utils.py** — function: base64url_decode, base64url_encode, bytes_from_int, bytes_to_number, der_to_raw_signature, force_bytes; 8 imports; module: utils
**warnings.py** — class: InsecureKeyLengthWarning, RemovedInPyjwt3Warning; module: warnings
**Optimiser.py** — class: Optimiser; 6 imports; method: Optimiser.__init__, Optimiser.consider_comms, Optimiser.consider_empty_community, Optimiser.max_comm_size, Optimiser.merge_nodes, Optimiser.merge_nodes_constrained; module: Optimiser
**VertexPartition.py** — class: CPMVertexPartition, LinearResolutionParameterVertexPartition, ModularityVertexPartition, MutableVertexPartition, RBConfigurationVertexPartition, RBERVertexPartition; 3 imports; method: CPMVertexPartition.Bipartite, CPMVertexPartition.__deepcopy__, CPMVertexPartition.__init__, LinearResolutionParameterVertexPartition.__init__, LinearResolutionParameterVertexPartition.bisect_value, LinearResolutionParameterVertexPartition.quality; module: VertexPartition
**__init__.py** — function: _delvewheel_patch_1_11_2; 24 imports; module: __init__
**functions.py** — function: _get_py_capsule, disjoint_union_attrs, find_partition, find_partition_multiplex, find_partition_temporal, get_attrs_or_nones; 12 imports; module: functions
**pynterface.cpp** — module: pynterface
**python_optimiser_interface.cpp** — module: python_optimiser_interface
**python_partition_interface.cpp** — module: python_partition_interface
**version.py** — 2 imports; module: version
**__init__.py** — 1 imports; module: __init__
**_compat.py** — 1 imports; module: _compat
**_punycode.py** — function: decode, encode, map_domain, to_ascii, to_unicode; 3 imports; module: _punycode
**parse.py** — function: convert, convert_file, convert_stdin, interactive, main, parse_args; 7 imports; module: parse; rationale: [NOTE] Remember to update README.md w/ the output of `markdown-it -h`
**entities.py** — 1 imports; module: entities
**html_blocks.py** — module: html_blocks
**html_re.py** — 1 imports; module: html_re
**normalize_url.py** — function: normalizeLink, normalizeLinkText, validateLink; 10 imports; module: normalize_url
**utils.py** — function: arrayReplaceAt, charCodeAt, charStrAt, escapeHtml, escapeRE, fromCodePoint; 6 imports; module: utils; rationale: [NOTE] this is equivalent to unicode case folding; unicode normalization
**__init__.py** — 3 imports; module: __init__
**parse_link_destination.py** — class: _Result; function: parseLinkDestination; 2 imports; method: _Result.__init__; module: parse_link_destination
**parse_link_label.py** — function: parseLinkLabel; 1 imports; module: parse_link_label
**parse_link_title.py** — class: _State; function: parseLinkTitle; 2 imports; method: _State.__init__, _State.__str__; module: parse_link_title
**main.py** — class: MarkdownIt; 26 imports; method: MarkdownIt.__getitem__, MarkdownIt.__init__, MarkdownIt.__repr__, MarkdownIt.add_render_rule, MarkdownIt.configure, MarkdownIt.disable; module: main
**parser_block.py** — class: ParserBlock; 10 imports; method: ParserBlock.__init__, ParserBlock.parse, ParserBlock.tokenize; module: parser_block
**parser_core.py** — class: ParserCore; 11 imports; method: ParserCore.__init__, ParserCore.process; module: parser_core
**parser_inline.py** — class: ParserInline; function: _default_terminator_re; 11 imports; method: ParserInline.__init__, ParserInline.add_terminator_char, ParserInline.parse, ParserInline.skipToken, ParserInline.tokenize; module: parser_inline; rationale: [NOTE] Don't confuse with "Markdown ASCII Punctuation" chars., [NOTE] this will cause links to behave incorrectly in the following case,, [TODO] remove this workaround when CM standard will allow nested links
**__init__.py** — class: gfm_like, gfm_like2; 4 imports; method: gfm_like.make, gfm_like2.make; module: __init__
**commonmark.py** — function: make; 1 imports; module: commonmark
**default.py** — function: make; 1 imports; module: default
**zero.py** — function: make; 1 imports; module: zero
**renderer.py** — class: RendererHTML, RendererProtocol; 11 imports; method: RendererHTML.__init__, RendererHTML.code_block, RendererHTML.code_inline, RendererHTML.fence, RendererHTML.hardbreak, RendererHTML.html_block; module: renderer
**ruler.py** — class: Rule, RuleOptionsType, Ruler, StateBase; 11 imports; method: Ruler.__compile__, Ruler.__find__, Ruler.__init__, Ruler.after, Ruler.at, Ruler.before; module: ruler
**__init__.py** — 13 imports; module: __init__
**blockquote.py** — function: _detect_alert, blockquote; 4 imports; module: blockquote; rationale: [NOTE] `startLine` here refers to the first content line of the
**code.py** — function: code; 2 imports; module: code
**fence.py** — function: make_fence_rule; 4 imports; module: fence
**heading.py** — function: heading; 4 imports; module: heading
**hr.py** — function: hr; 3 imports; module: hr
**html_block.py** — function: html_block; 6 imports; module: html_block
**lheading.py** — function: lheading; 2 imports; module: lheading
**list.py** — function: _detect_task_checkbox, list_block, markTightParagraphs, skipBulletListMarker, skipOrderedListMarker; 3 imports; module: list
**paragraph.py** — function: paragraph; 2 imports; module: paragraph
**reference.py** — function: getNextLine, reference; 5 imports; module: reference
**state_block.py** — class: StateBlock; 8 imports; method: StateBlock.__init__, StateBlock.__repr__, StateBlock.getLines, StateBlock.isEmpty, StateBlock.is_code_block, StateBlock.push; module: state_block
**table.py** — function: escapedSplit, getLine, table; 5 imports; module: table; rationale: [NOTE] autocomplete count can be negative if user specifies more columns than header,
**__init__.py** — 8 imports; module: __init__
**block.py** — function: block; 2 imports; module: block
**inline.py** — function: inline; 1 imports; module: inline
**linkify.py** — class: _LinkType; function: linkify; 8 imports; module: linkify
**normalize.py** — function: normalize; 2 imports; module: normalize
**replacements.py** — function: replace, replaceFn, replace_rare, replace_scoped; 5 imports; module: replacements
**smartquotes.py** — function: process_inlines, replaceAt, smartquotes; 9 imports; module: smartquotes
**state_core.py** — class: StateCore; 6 imports; method: StateCore.__init__; module: state_core
**text_join.py** — function: text_join; 3 imports; module: text_join
**__init__.py** — 15 imports; module: __init__
**autolink.py** — function: autolink; 2 imports; module: autolink
**backticks.py** — function: backtick; 2 imports; module: backticks
**balance_pairs.py** — function: link_pairs, processDelimiters; 3 imports; module: balance_pairs
**emphasis.py** — function: _postProcess, postProcess, tokenize; 3 imports; module: emphasis
**entity.py** — function: entity; 5 imports; module: entity
**escape.py** — function: escape; 2 imports; module: escape
**fragments_join.py** — function: fragments_join; 1 imports; module: fragments_join
**html_inline.py** — function: html_inline, isLetter; 4 imports; module: html_inline
**image.py** — function: image; 5 imports; module: image
**link.py** — function: link; 3 imports; module: link
**linkify.py** — function: linkify; 2 imports; module: linkify
**newline.py** — function: newline; 3 imports; module: newline
**state_inline.py** — class: Delimiter, Scanned, StateInline; 13 imports; method: StateInline.__init__, StateInline.__repr__, StateInline.push, StateInline.pushPending, StateInline.scanDelims; module: state_inline
**strikethrough.py** — function: _postProcess, postProcess, tokenize; 3 imports; module: strikethrough
**text.py** — function: text; 1 imports; module: text
**token.py** — class: Token; function: convert_attrs; 7 imports; method: Token.__post_init__, Token.as_dict, Token.attrGet, Token.attrIndex, Token.attrItems, Token.attrJoin; module: token
**tree.py** — class: SyntaxTreeNode, _NesterTokens; 9 imports; method: SyntaxTreeNode.__getitem__, SyntaxTreeNode.__init__, SyntaxTreeNode.__repr__, SyntaxTreeNode._add_child, SyntaxTreeNode._attribute_token, SyntaxTreeNode._set_children_from_tokens; module: tree
**utils.py** — class: OptionsDict, OptionsType, PresetType; function: read_fixture_file; 10 imports; method: OptionsDict.__delitem__, OptionsDict.__getitem__, OptionsDict.__init__, OptionsDict.__iter__, OptionsDict.__len__, OptionsDict.__repr__; module: utils; rationale: [NOTE] could use TypeAlias in python 3.10, [NOTE] ideally we would probably just remove attribute access entirely,
**__init__.py** — 65 imports; module: __init__
**__init__.py** — 1 imports; module: __init__
**claude.py** — function: get_claude_config_path, get_uv_path, update_claude_config; 7 imports; module: claude
**cli.py** — function: _build_uv_command, _get_npx_command, _import_server, _parse_env_var, _parse_file_path, dev; 14 imports; module: cli
**__main__.py** — function: cli, main, message_handler, run_session; 16 imports; module: __main__
**__init__.py** — 6 imports; module: __init__
**exceptions.py** — class: OAuthFlowError, OAuthRegistrationError, OAuthTokenError; module: exceptions
**client_credentials.py** — class: ClientCredentialsOAuthProvider, JWTParameters, PrivateKeyJWTOAuthProvider, RFC7523OAuthClientProvider, SignedJWTParameters; function: static_assertion_provider; 17 imports; method: ClientCredentialsOAuthProvider.__init__, ClientCredentialsOAuthProvider._exchange_token_client_credentials, ClientCredentialsOAuthProvider._initialize, ClientCredentialsOAuthProvider._perform_authorization, JWTParameters.to_assertion, PrivateKeyJWTOAuthProvider.__init__; module: client_credentials
**oauth2.py** — class: OAuthClientProvider, OAuthContext, PKCEParameters, TokenStorage; 48 imports; method: OAuthClientProvider.__init__, OAuthClientProvider._add_auth_header, OAuthClientProvider._exchange_token_authorization_code, OAuthClientProvider._get_token_endpoint, OAuthClientProvider._handle_oauth_metadata_response, OAuthClientProvider._handle_protected_resource_response; module: oauth2; rationale: [TODO] try all authorization_servers to find the OASM
**utils.py** — function: build_oauth_authorization_server_metadata_discovery_urls, build_protected_resource_metadata_discovery_urls, create_client_info_from_metadata_url, create_client_registration_request, create_oauth_metadata_request, extract_field_from_www_auth; 17 imports; module: utils
**__init__.py** — 1 imports; module: __init__
**task_handlers.py** — class: CancelTaskHandlerFnT, ExperimentalTaskHandlers, GetTaskHandlerFnT, GetTaskResultHandlerFnT, ListTasksHandlerFnT, TaskAugmentedElicitationFnT; function: default_cancel_task_handler, default_get_task_handler, default_get_task_result_handler, default_list_tasks_handler, default_task_augmented_elicitation, default_task_augmented_sampling; 10 imports; method: CancelTaskHandlerFnT.__call__, ExperimentalTaskHandlers.build_capability, ExperimentalTaskHandlers.handle_request, ExperimentalTaskHandlers.handles_request, GetTaskHandlerFnT.__call__, GetTaskResultHandlerFnT.__call__; module: task_handlers
**tasks.py** — class: ExperimentalClientFeatures; 7 imports; method: ExperimentalClientFeatures.__init__, ExperimentalClientFeatures.call_tool_as_task, ExperimentalClientFeatures.cancel_task, ExperimentalClientFeatures.get_task, ExperimentalClientFeatures.get_task_result, ExperimentalClientFeatures.list_tasks; module: tasks
**session.py** — class: ClientSession, ElicitationFnT, ListRootsFnT, LoggingFnT, MessageHandlerFnT, SamplingFnT; function: _default_elicitation_callback, _default_list_roots_callback, _default_logging_callback, _default_message_handler, _default_sampling_callback; 23 imports; method: ClientSession.__init__, ClientSession._handle_incoming, ClientSession._received_notification, ClientSession._received_request, ClientSession._validate_tool_result, ClientSession.call_tool; module: session; rationale: [NOTE] don't clear the cache, as we may be using a cursor, [TODO] Should this be based on whether we
**session_group.py** — class: ClientSessionGroup, ClientSessionParameters, SseServerParameters, StreamableHttpParameters; 27 imports; method: ClientSessionGroup.__aenter__, ClientSessionGroup.__aexit__, ClientSessionGroup.__init__, ClientSessionGroup._aggregate_components, ClientSessionGroup._component_name, ClientSessionGroup._establish_session; module: session_group
**sse.py** — function: _extract_session_id_from_endpoint, remove_request_params, sse_client; 18 imports; module: sse
**__init__.py** — class: StdioServerParameters; function: _create_platform_compatible_process, _get_executable_command, _terminate_process_tree, get_default_environment, stdio_client; 22 imports; module: __init__
**streamable_http.py** — class: RequestContext, ResumptionError, StreamableHTTPError, StreamableHTTPTransport; function: streamable_http_client, streamablehttp_client; 32 imports; method: StreamableHTTPTransport.__init__, StreamableHTTPTransport._handle_json_response, StreamableHTTPTransport._handle_post_request, StreamableHTTPTransport._handle_reconnection, StreamableHTTPTransport._handle_resumption_request, StreamableHTTPTransport._handle_sse_event; module: streamable_http
**websocket.py** — function: websocket_client; 12 imports; module: websocket
**__init__.py** — module: __init__
**__init__.py** — module: __init__
**utilities.py** — function: terminate_posix_process_tree; 5 imports; module: utilities
**__init__.py** — module: __init__
**utilities.py** — class: FallbackProcess; function: _create_job_object, _create_windows_fallback_process, _maybe_assign_process_to_job, create_windows_process, get_windows_executable_command, terminate_windows_process; 18 imports; method: FallbackProcess.__aenter__, FallbackProcess.__aexit__, FallbackProcess.__init__, FallbackProcess.kill, FallbackProcess.pid, FallbackProcess.terminate; module: utilities
**__init__.py** — 4 imports; module: __init__
**__main__.py** — function: main, receive_loop; 9 imports; module: __main__
**__init__.py** — module: __init__
**errors.py** — function: stringify_pydantic_error; 1 imports; module: errors
**__init__.py** — module: __init__
**authorize.py** — class: AnyUrlModel, AuthorizationErrorResponse, AuthorizationHandler, AuthorizationRequest; function: best_effort_extract_string; 23 imports; method: AuthorizationHandler.handle; module: authorize
**metadata.py** — class: MetadataHandler, ProtectedResourceMetadataHandler; 6 imports; method: MetadataHandler.handle, ProtectedResourceMetadataHandler.handle; module: metadata
**register.py** — class: RegistrationErrorResponse, RegistrationHandler, RegistrationRequest; 18 imports; method: RegistrationHandler.handle; module: register
**revoke.py** — class: RevocationErrorResponse, RevocationHandler, RevocationRequest; 15 imports; method: RevocationHandler.handle; module: revoke
**token.py** — class: AuthorizationCodeRequest, RefreshTokenRequest, TokenErrorResponse, TokenHandler, TokenRequest, TokenSuccessResponse; 22 imports; method: TokenHandler.handle, TokenHandler.response; module: token
**json_response.py** — class: PydanticJSONResponse; 2 imports; method: PydanticJSONResponse.render; module: json_response
**__init__.py** — module: __init__
**auth_context.py** — class: AuthContextMiddleware; function: get_access_token; 7 imports; method: AuthContextMiddleware.__call__, AuthContextMiddleware.__init__; module: auth_context
**bearer_auth.py** — class: AuthenticatedUser, BearerAuthBackend, RequireAuthMiddleware; 13 imports; method: AuthenticatedUser.__init__, BearerAuthBackend.__init__, BearerAuthBackend.authenticate, RequireAuthMiddleware.__call__, RequireAuthMiddleware.__init__, RequireAuthMiddleware._send_auth_error; module: bearer_auth
**client_auth.py** — class: AuthenticationError, ClientAuthenticator; 9 imports; method: AuthenticationError.__init__, ClientAuthenticator.__init__, ClientAuthenticator.authenticate_request; module: client_auth
**provider.py** — class: AccessToken, AuthorizationCode, AuthorizationParams, AuthorizeError, OAuthAuthorizationServerProvider, ProviderTokenVerifier; function: construct_redirect_uri; 13 imports; method: OAuthAuthorizationServerProvider.authorize, OAuthAuthorizationServerProvider.exchange_authorization_code, OAuthAuthorizationServerProvider.exchange_refresh_token, OAuthAuthorizationServerProvider.get_client, OAuthAuthorizationServerProvider.load_access_token, OAuthAuthorizationServerProvider.load_authorization_code; module: provider; rationale: [NOTE] FastMCP doesn't render any of these types in the user response, so it's
**routes.py** — function: build_metadata, build_resource_metadata_url, cors_middleware, create_auth_routes, create_protected_resource_routes, validate_issuer_url; 24 imports; module: routes
**settings.py** — class: AuthSettings, ClientRegistrationOptions, RevocationOptions; 3 imports; module: settings
**elicitation.py** — class: AcceptedElicitation, AcceptedUrlElicitation, CancelledElicitation, DeclinedElicitation; function: _is_primitive_field, _is_string_sequence, _validate_elicitation_schema, elicit_url, elicit_with_validation; 12 imports; module: elicitation
**__init__.py** — module: __init__
**request_context.py** — class: Experimental; 21 imports; method: Experimental.can_use_tool, Experimental.client_supports_tasks, Experimental.is_task, Experimental.run_task, Experimental.validate_for_tool, Experimental.validate_task_mode; module: request_context
**session_features.py** — class: ExperimentalServerSessionFeatures; 11 imports; method: ExperimentalServerSessionFeatures.__init__, ExperimentalServerSessionFeatures.create_message_as_task, ExperimentalServerSessionFeatures.elicit_as_task, ExperimentalServerSessionFeatures.get_task, ExperimentalServerSessionFeatures.get_task_result, ExperimentalServerSessionFeatures.poll_task; module: session_features
**task_context.py** — class: ServerTaskContext; 37 imports; method: ServerTaskContext.__init__, ServerTaskContext._check_elicitation_capability, ServerTaskContext._check_sampling_capability, ServerTaskContext._send_notification, ServerTaskContext.complete, ServerTaskContext.create_message; module: task_context
**task_result_handler.py** — class: TaskResultHandler; 19 imports; method: TaskResultHandler.__init__, TaskResultHandler._deliver_queued_messages, TaskResultHandler._wait_for_task_update, TaskResultHandler.handle, TaskResultHandler.route_error, TaskResultHandler.route_response; module: task_result_handler
**task_support.py** — class: TaskSupport; 12 imports; method: TaskSupport.__post_init__, TaskSupport.configure_session, TaskSupport.in_memory, TaskSupport.run, TaskSupport.task_group; module: task_support
**__init__.py** — 6 imports; module: __init__
**exceptions.py** — class: FastMCPError, InvalidSignature, ResourceError, ToolError, ValidationError; module: exceptions
**__init__.py** — 2 imports; module: __init__
**base.py** — class: AssistantMessage, Message, Prompt, PromptArgument, UserMessage; 23 imports; method: AssistantMessage.__init__, Message.__init__, Prompt.from_function, Prompt.render, UserMessage.__init__; module: base
**manager.py** — class: PromptManager; 10 imports; method: PromptManager.__init__, PromptManager.add_prompt, PromptManager.get_prompt, PromptManager.list_prompts, PromptManager.render_prompt; module: manager
**__init__.py** — 9 imports; module: __init__
**base.py** — class: Resource; 12 imports; method: Resource.read, Resource.set_default_name; module: base
**resource_manager.py** — class: ResourceManager; 14 imports; method: ResourceManager.__init__, ResourceManager.add_resource, ResourceManager.add_template, ResourceManager.get_resource, ResourceManager.list_resources, ResourceManager.list_templates; module: resource_manager
**templates.py** — class: ResourceTemplate; 20 imports; method: ResourceTemplate.create_resource, ResourceTemplate.from_function, ResourceTemplate.matches; module: templates
**types.py** — class: BinaryResource, DirectoryResource, FileResource, FunctionResource, HttpResource, TextResource; 17 imports; method: BinaryResource.read, DirectoryResource.list_files, DirectoryResource.read, DirectoryResource.validate_absolute_path, FileResource.read, FileResource.set_binary_from_mime_type; module: types
**server.py** — class: Context, FastMCP, Settings, StreamableHTTPASGIApp; function: lifespan_wrapper; 82 imports; method: Context.__init__, Context.client_id, Context.close_sse_stream, Context.close_standalone_sse_stream, Context.debug, Context.elicit; module: server; rationale: [NOTE] we disable the lowlevel server's input validation.
**__init__.py** — 2 imports; module: __init__
**base.py** — class: Tool; function: _is_async_callable; 21 imports; method: Tool.from_function, Tool.output_schema, Tool.run; module: base
**tool_manager.py** — class: ToolManager; 13 imports; method: ToolManager.__init__, ToolManager.add_tool, ToolManager.call_tool, ToolManager.get_tool, ToolManager.list_tools, ToolManager.remove_tool; module: tool_manager
**__init__.py** — module: __init__
**context_injection.py** — function: find_context_parameter, inject_context; 6 imports; module: context_injection
**func_metadata.py** — class: ArgModelBase, FuncMetadata, StrictJsonSchema; function: _convert_to_content, _create_dict_model, _create_model_from_class, _create_model_from_typeddict, _create_wrapped_model, _try_create_model_and_schema; 37 imports; method: ArgModelBase.model_dump_one_level, FuncMetadata.call_fn_with_arg_validation, FuncMetadata.convert_result, FuncMetadata.pre_parse_json, StrictJsonSchema.emit_warning; module: func_metadata; rationale: [TODO] should we use the original annotation? We are loosing any potential `Annotated`
**logging.py** — function: configure_logging, get_logger; 4 imports; module: logging
**types.py** — class: Audio, Image; 4 imports; method: Audio.__init__, Audio._get_mime_type, Audio.to_audio_content, Image.__init__, Image._get_mime_type, Image.to_image_content; module: types
**__init__.py** — 2 imports; module: __init__
**experimental.py** — class: ExperimentalHandlers; 32 imports; method: ExperimentalHandlers.__init__, ExperimentalHandlers._register_default_task_handlers, ExperimentalHandlers.cancel_task, ExperimentalHandlers.enable_tasks, ExperimentalHandlers.get_task, ExperimentalHandlers.get_task_result; module: experimental
**func_inspection.py** — function: create_call_wrapper; 5 imports; module: func_inspection
**helper_types.py** — class: ReadResourceContents; 2 imports; module: helper_types
**server.py** — class: NotificationOptions, Server; function: _ping_handler, lifespan; 38 imports; method: NotificationOptions.__init__, Server.__init__, Server._get_cached_tool_definition, Server._handle_message, Server._handle_notification, Server._handle_request; module: server; rationale: [NOTE] ResourceContents uses Field(alias="_meta"), so we must use the alias key
**models.py** — class: InitializationOptions; 3 imports; module: models
**session.py** — class: InitializationState, ServerSession; 21 imports; method: ServerSession.__init__, ServerSession._build_create_message_request, ServerSession._build_elicit_form_request, ServerSession._build_elicit_url_request, ServerSession._handle_incoming, ServerSession._receive_loop; module: session
**sse.py** — class: SseServerTransport; 21 imports; method: SseServerTransport.__init__, SseServerTransport.connect_sse, SseServerTransport.handle_post_message; module: sse
**stdio.py** — function: stdio_server; 9 imports; module: stdio
**streamable_http.py** — class: EventMessage, EventStore, StreamableHTTPServerTransport; 38 imports; method: EventStore.replay_events_after, EventStore.store_event, StreamableHTTPServerTransport.__init__, StreamableHTTPServerTransport._check_accept_headers, StreamableHTTPServerTransport._check_content_type, StreamableHTTPServerTransport._clean_up_memory_streams; module: streamable_http
**streamable_http_manager.py** — class: StreamableHTTPSessionManager; 22 imports; method: StreamableHTTPSessionManager.__init__, StreamableHTTPSessionManager._handle_stateful_request, StreamableHTTPSessionManager._handle_stateless_request, StreamableHTTPSessionManager.handle_request, StreamableHTTPSessionManager.run; module: streamable_http_manager; rationale: [TODO] Align error code once spec clarifies
**transport_security.py** — class: TransportSecurityMiddleware, TransportSecuritySettings; 5 imports; method: TransportSecurityMiddleware.__init__, TransportSecurityMiddleware._validate_content_type, TransportSecurityMiddleware._validate_host, TransportSecurityMiddleware._validate_origin, TransportSecurityMiddleware.validate_request; module: transport_security
**validation.py** — function: check_sampling_tools_capability, validate_sampling_tools, validate_tool_use_result_messages; 7 imports; module: validation
**websocket.py** — function: websocket_server; 12 imports; module: websocket
**_httpx_utils.py** — class: McpHttpClientFactory; function: create_mcp_http_client; 3 imports; method: McpHttpClientFactory.__call__; module: _httpx_utils
**auth.py** — class: InvalidRedirectUriError, InvalidScopeError, OAuthClientInformationFull, OAuthClientMetadata, OAuthMetadata, OAuthToken; 7 imports; method: InvalidRedirectUriError.__init__, InvalidScopeError.__init__, OAuthClientMetadata._empty_string_optional_url_to_none, OAuthClientMetadata.validate_redirect_uri, OAuthClientMetadata.validate_scope, OAuthToken.normalize_token_type; module: auth
**auth_utils.py** — function: calculate_token_expiry, check_resource_allowed, resource_url_from_server_url; 6 imports; module: auth_utils
**context.py** — class: RequestContext; 9 imports; module: context; rationale: [NOTE] This is typed as Any to avoid circular imports. The actual type is
**exceptions.py** — class: McpError, UrlElicitationRequiredError; 6 imports; method: McpError.__init__, UrlElicitationRequiredError.__init__, UrlElicitationRequiredError.elicitations, UrlElicitationRequiredError.from_error; module: exceptions
**__init__.py** — module: __init__
**__init__.py** — module: __init__
**capabilities.py** — function: check_tasks_capability, has_task_augmented_elicitation, has_task_augmented_sampling, require_task_augmented_elicitation, require_task_augmented_sampling; 5 imports; module: capabilities
**context.py** — class: TaskContext; 5 imports; method: TaskContext.__init__, TaskContext.complete, TaskContext.fail, TaskContext.is_cancelled, TaskContext.request_cancellation, TaskContext.task; module: context
**helpers.py** — function: cancel_task, create_task_state, generate_task_id, is_terminal, task_execution; 18 imports; module: helpers
**in_memory_task_store.py** — class: InMemoryTaskStore, StoredTask; 13 imports; method: InMemoryTaskStore.__init__, InMemoryTaskStore._calculate_expiry, InMemoryTaskStore._cleanup_expired, InMemoryTaskStore._is_expired, InMemoryTaskStore.cleanup, InMemoryTaskStore.create_task; module: in_memory_task_store
**message_queue.py** — class: InMemoryTaskMessageQueue, QueuedMessage, TaskMessageQueue; 13 imports; method: InMemoryTaskMessageQueue.__init__, InMemoryTaskMessageQueue._get_queue, InMemoryTaskMessageQueue.cleanup, InMemoryTaskMessageQueue.clear, InMemoryTaskMessageQueue.dequeue, InMemoryTaskMessageQueue.enqueue; module: message_queue
**polling.py** — function: poll_until_terminal; 6 imports; module: polling
**resolver.py** — class: Resolver; 4 imports; method: Resolver.__init__, Resolver.done, Resolver.set_exception, Resolver.set_result, Resolver.wait; module: resolver
**store.py** — class: TaskStore; 6 imports; method: TaskStore.create_task, TaskStore.delete_task, TaskStore.get_result, TaskStore.get_task, TaskStore.list_tasks, TaskStore.notify_update; module: store
**memory.py** — function: create_client_server_memory_streams, create_connected_server_and_client_session; 18 imports; module: memory
**message.py** — class: ClientMessageMetadata, ServerMessageMetadata, SessionMessage; 5 imports; module: message
**metadata_utils.py** — function: get_display_name; 5 imports; module: metadata_utils
**progress.py** — class: Progress, ProgressContext; function: progress; 15 imports; method: ProgressContext.progress; module: progress
**response_router.py** — class: ResponseRouter; 4 imports; method: ResponseRouter.route_error, ResponseRouter.route_response; module: response_router
**session.py** — class: BaseSession, ProgressFnT, RequestResponder; 37 imports; method: BaseSession.__aenter__, BaseSession.__aexit__, BaseSession.__init__, BaseSession._handle_incoming, BaseSession._handle_response, BaseSession._normalize_request_id; module: session
**tool_name_validation.py** — class: ToolNameValidationResult; function: issue_tool_name_warning, validate_and_warn_tool_name, validate_tool_name; 5 imports; module: tool_name_validation
**version.py** — 1 imports; module: version
**types.py** — class: Annotations, AudioContent, BaseMetadata, BlobResourceContents, CallToolRequest, CallToolRequestParams; 17 imports; method: CreateMessageResultWithTools.content_as_list, SamplingMessage.content_as_list; module: types
**__init__.py** — 9 imports; module: __init__
**_decode.py** — function: decode, get_decode_cache, repl_func_with_cache; 4 imports; module: _decode
**_encode.py** — function: encode, get_encode_cache; 6 imports; module: _encode
**_format.py** — function: format; 3 imports; module: _format
**_parse.py** — class: MutableURL; function: url_parse; 4 imports; method: MutableURL.__init__, MutableURL.parse, MutableURL.parse_host; module: _parse
**_url.py** — class: URL; 2 imports; module: _url
**__init__.py** — 7 imports; module: __init__
**decoders.py** — 1 imports; module: decoders
**exceptions.py** — 1 imports; module: exceptions
**multipart.py** — 1 imports; module: multipart
**__init__.py** — function: __getattr__; 24 imports; module: __init__
**__init__.py** — 128 imports; module: __init__
**__init__.py** — 14 imports; module: __init__
**clique.py** — function: clique_removal, large_clique_size, max_clique, maximum_independent_set; 3 imports; module: clique
**clustering_coefficient.py** — function: average_clustering; 3 imports; module: clustering_coefficient
**connectivity.py** — function: _bidirectional_pred_succ, _bidirectional_shortest_path, all_pairs_node_connectivity, local_node_connectivity, node_connectivity; 3 imports; module: connectivity
**density.py** — function: _fista, _fractional_peeling, _greedy_plus_plus, densest_subgraph; 3 imports; module: density
**distance_measures.py** — function: _two_sweep_directed, _two_sweep_undirected, diameter; 2 imports; module: distance_measures
**dominating_set.py** — function: min_edge_dominating_set, min_weighted_dominating_set; 3 imports; module: dominating_set
**kcomponents.py** — class: _AntiGraph; function: _cliques_heuristic, _same, k_components; 8 imports; method: _AntiGraph.__getitem__, _AntiGraph.adj, _AntiGraph.adjacency, _AntiGraph.degree, _AntiGraph.neighbors, _AntiGraph.single_edge_dict; module: kcomponents
**matching.py** — function: min_maximal_matching; 1 imports; module: matching
**maxcut.py** — function: _swap_node_partition, one_exchange, randomized_partitioning; 3 imports; module: maxcut
**ramsey.py** — function: ramsey_R2; 3 imports; module: ramsey
**steinertree.py** — function: _kou_steiner_tree, _mehlhorn_steiner_tree, _remove_nonterminal_leaves, metric_closure, steiner_tree; 5 imports; module: steinertree
**test_approx_clust_coeff.py** — function: test_complete, test_dodecahedral, test_empty, test_petersen, test_petersen_seed, test_tetrahedral; 2 imports; module: test_approx_clust_coeff
**test_clique.py** — class: TestCliqueRemoval, TestMaxClique; function: is_clique, is_independent_set, test_independent_set, test_large_clique_size; 5 imports; method: TestCliqueRemoval.test_barbell_graph, TestCliqueRemoval.test_complete_graph, TestCliqueRemoval.test_trivial_graph, TestMaxClique.test_complete_graph, TestMaxClique.test_maximal_by_cardinality, TestMaxClique.test_null_graph; module: test_clique
**test_connectivity.py** — class: TestAllPairsNodeConnectivityApprox; function: test_complete_graphs, test_directed_node_connectivity, test_dodecahedral, test_empty_graphs, test_global_node_connectivity, test_missing_source; 3 imports; method: TestAllPairsNodeConnectivityApprox.setup_class, TestAllPairsNodeConnectivityApprox.test_all_pairs_connectivity_nbunch, TestAllPairsNodeConnectivityApprox.test_complete, TestAllPairsNodeConnectivityApprox.test_cutoff, TestAllPairsNodeConnectivityApprox.test_cycles, TestAllPairsNodeConnectivityApprox.test_paths; module: test_connectivity
**test_density.py** — function: bipartite_and_clique_example, close_cliques_example, test_fista_big_dataset, test_fista_bipartite_and_clique, test_fista_close_cliques, test_gh_8271; 3 imports; module: test_density; rationale: [NOTE] iterations=12 fails to ID the densest subgraph, [NOTE] iterations=12 fails to identify densest subgraph, [NOTE] iterations=185 fails to ID the densest subgraph
**test_distance_measures.py** — class: TestDiameter; 3 imports; method: TestDiameter.test_complete_directed_graph, TestDiameter.test_complete_undirected_graph, TestDiameter.test_directed_non_strongly_connected, TestDiameter.test_directed_path_graph, TestDiameter.test_null_graph, TestDiameter.test_single_node; module: test_distance_measures
**test_dominating_set.py** — class: TestMinWeightDominatingSet; 4 imports; method: TestMinWeightDominatingSet.test_min_edge_dominating_set, TestMinWeightDominatingSet.test_min_weighted_dominating_set, TestMinWeightDominatingSet.test_null_graph, TestMinWeightDominatingSet.test_star_graph; module: test_dominating_set
**test_kcomponents.py** — class: TestAntiGraph; function: _check_connectivity, build_k_number_dict, graph_example_1, test_directed, test_example_1, test_example_1_detail_3_and_4; 5 imports; method: TestAntiGraph.setup_class, TestAntiGraph.test_adj, TestAntiGraph.test_adjacency, TestAntiGraph.test_connected_components, TestAntiGraph.test_core_number, TestAntiGraph.test_degree; module: test_kcomponents
**test_matching.py** — function: test_min_maximal_matching; 2 imports; module: test_matching
**test_maxcut.py** — function: _cut_is_locally_optimal, _is_valid_cut, test_negative_weights, test_one_exchange_basic, test_one_exchange_optimal, test_raises_on_directed_and_multigraphs; 4 imports; module: test_maxcut
**test_ramsey.py** — function: test_ramsey; 2 imports; module: test_ramsey
**test_steinertree.py** — class: TestSteinerTree; function: method, test_steiner_tree_method_invalid, test_steiner_tree_methods, test_steiner_tree_multigraph_weight_attribute, test_steiner_tree_non_terminal_leaves_multigraph_self_loop_edges, test_steiner_tree_remove_non_terminal_leaves_self_loop_edges; 6 imports; method: TestSteinerTree.setup_class, TestSteinerTree.test_connected_metric_closure, TestSteinerTree.test_metric_closure, TestSteinerTree.test_multigraph_steiner_tree, TestSteinerTree.test_remove_nonterminal_leaves, TestSteinerTree.test_steiner_tree; module: test_steinertree
**test_traveling_salesman.py** — class: TestBase, TestGreedyTSP, TestSimulatedAnnealingTSP, TestThresholdAcceptingTSP; function: test_TSP_alternate_weight, test_TSP_incomplete_graph_short_path, test_TSP_method, test_TSP_unweighted, test_TSP_weighted, test_asadpour_disconnected_graph; 5 imports; method: TestBase.setup_class, TestGreedyTSP.test_greedy, TestGreedyTSP.test_ignore_selfloops, TestGreedyTSP.test_not_complete_graph, TestGreedyTSP.test_not_weighted_graph, TestGreedyTSP.test_two_nodes; module: test_traveling_salesman
**test_treewidth.py** — class: TestTreewidthMinDegree, TestTreewidthMinFillIn; function: is_tree_decomp; 6 imports; method: TestTreewidthMinDegree.setup_class, TestTreewidthMinDegree.test_empty_graph, TestTreewidthMinDegree.test_heuristic_abort, TestTreewidthMinDegree.test_heuristic_first_steps, TestTreewidthMinDegree.test_not_sortable_nodes, TestTreewidthMinDegree.test_petersen_graph; module: test_treewidth
**test_vertex_cover.py** — class: TestMWVC; function: is_cover; 2 imports; method: TestMWVC.test_unweighted_directed, TestMWVC.test_unweighted_self_loop, TestMWVC.test_unweighted_undirected, TestMWVC.test_weighted; module: test_vertex_cover
**traveling_salesman.py** — function: _shortcutting, asadpour_atsp, christofides, greedy_tsp, held_karp_ascent, move_one_node; 11 imports; module: traveling_salesman; rationale: [TODO] this branch does not restore original_edge_weights of G!
**treewidth.py** — class: MinDegreeHeuristic; function: min_fill_in_heuristic, treewidth_decomp, treewidth_min_degree, treewidth_min_fill_in; 7 imports; method: MinDegreeHeuristic.__init__, MinDegreeHeuristic.best_node; module: treewidth
**vertex_cover.py** — function: min_weighted_vertex_cover; 1 imports; module: vertex_cover
**__init__.py** — 5 imports; module: __init__
**connectivity.py** — function: average_degree_connectivity; 2 imports; module: connectivity
**correlation.py** — function: _numeric_ac, attribute_ac, attribute_assortativity_coefficient, degree_assortativity_coefficient, degree_pearson_correlation_coefficient, numeric_assortativity_coefficient; 6 imports; module: correlation
**mixing.py** — function: attribute_mixing_dict, attribute_mixing_matrix, degree_mixing_dict, degree_mixing_matrix, mixing_dict; 4 imports; module: mixing
**neighbor_degree.py** — function: average_neighbor_degree; 1 imports; module: neighbor_degree
**pairs.py** — function: node_attribute_xy, node_degree_xy; 1 imports; module: pairs
**base_test.py** — class: BaseTestAttributeMixing, BaseTestDegreeMixing; 1 imports; method: BaseTestAttributeMixing.setup_class, BaseTestDegreeMixing.setup_class; module: base_test
**test_connectivity.py** — class: TestNeighborConnectivity; 3 imports; method: TestNeighborConnectivity.test_degree_barrat, TestNeighborConnectivity.test_degree_p4, TestNeighborConnectivity.test_degree_p4_weighted, TestNeighborConnectivity.test_in_out_weight, TestNeighborConnectivity.test_invalid_source, TestNeighborConnectivity.test_invalid_target; module: test_connectivity
**test_correlation.py** — class: TestAttributeMixingCorrelation, TestDegreeMixingCorrelation; 5 imports; method: TestAttributeMixingCorrelation.test_assortativity_node_kwargs, TestAttributeMixingCorrelation.test_attribute_assortativity, TestAttributeMixingCorrelation.test_attribute_assortativity_coefficient, TestAttributeMixingCorrelation.test_attribute_assortativity_coefficient2, TestAttributeMixingCorrelation.test_attribute_assortativity_directed, TestAttributeMixingCorrelation.test_attribute_assortativity_float; module: test_correlation
**test_mixing.py** — class: TestAttributeMixingDict, TestAttributeMixingMatrix, TestDegreeMixingDict, TestDegreeMixingMatrix; 4 imports; method: TestAttributeMixingDict.test_attribute_mixing_dict_directed, TestAttributeMixingDict.test_attribute_mixing_dict_multigraph, TestAttributeMixingDict.test_attribute_mixing_dict_undirected, TestAttributeMixingMatrix.test_attribute_mixing_matrix_directed, TestAttributeMixingMatrix.test_attribute_mixing_matrix_float, TestAttributeMixingMatrix.test_attribute_mixing_matrix_multigraph; module: test_mixing
**test_neighbor_degree.py** — class: TestAverageNeighbor; 2 imports; method: TestAverageNeighbor.test_degree_barrat, TestAverageNeighbor.test_degree_k4, TestAverageNeighbor.test_degree_k4_nodes, TestAverageNeighbor.test_degree_p4, TestAverageNeighbor.test_degree_p4_weighted, TestAverageNeighbor.test_error_invalid_source_target; module: test_neighbor_degree
**test_pairs.py** — class: TestAttributeMixingXY, TestDegreeMixingXY; 3 imports; method: TestAttributeMixingXY.test_node_attribute_xy_directed, TestAttributeMixingXY.test_node_attribute_xy_multigraph, TestAttributeMixingXY.test_node_attribute_xy_selfloop, TestAttributeMixingXY.test_node_attribute_xy_undirected, TestAttributeMixingXY.test_node_attribute_xy_undirected_nodes, TestDegreeMixingXY.test_node_degree_xy_directed; module: test_pairs
**asteroidal.py** — function: create_component_structure, find_asteroidal_triple, is_at_free; 2 imports; module: asteroidal
**__init__.py** — 13 imports; module: __init__
**basic.py** — function: color, degrees, density, is_bipartite, is_bipartite_node_set, sets; 4 imports; module: basic
**centrality.py** — function: betweenness_centrality, closeness_centrality, degree_centrality; 1 imports; module: centrality
**cluster.py** — function: _four_cycles, _threepaths, average_clustering, cc_dot, cc_max, cc_min; 2 imports; module: cluster
**covering.py** — function: min_edge_cover; 4 imports; module: covering
**edgelist.py** — function: generate_edgelist, parse_edgelist, read_edgelist, write_edgelist; 4 imports; module: edgelist
**extendability.py** — function: maximal_extendability; 2 imports; module: extendability
**generators.py** — function: _add_nodes_with_bipartite_label, alternating_havel_hakimi_graph, complete_bipartite_graph, configuration_model, gnmk_random_graph, havel_hakimi_graph; 6 imports; module: generators
**link_analysis.py** — function: _clean_personalization_dict, birank; 4 imports; module: link_analysis
**matching.py** — function: _connected_by_alternating_paths, _is_connected_by_alternating_path, eppstein_matching, hopcroft_karp_matching, minimum_weight_full_matching, to_vertex_cover; 7 imports; module: matching
**matrix.py** — function: _validate_initialize_bipartite_nodelists, biadjacency_matrix, from_biadjacency_matrix; 4 imports; module: matrix
**projection.py** — function: collaboration_weighted_projected_graph, generic_weighted_projected_graph, overlap_weighted_projected_graph, projected_graph, weighted_projected_graph; 3 imports; module: projection
**redundancy.py** — function: _node_redundancy, node_redundancy; 3 imports; module: redundancy
**spectral.py** — function: spectral_bipartivity; 2 imports; module: spectral
**test_basic.py** — class: TestBipartiteBasic; 3 imports; method: TestBipartiteBasic.test_biadjacency_matrix, TestBipartiteBasic.test_biadjacency_matrix_order, TestBipartiteBasic.test_biadjacency_matrix_weight, TestBipartiteBasic.test_bipartite_color, TestBipartiteBasic.test_bipartite_degrees, TestBipartiteBasic.test_bipartite_density; module: test_basic
**test_centrality.py** — class: TestBipartiteCentrality; 3 imports; method: TestBipartiteCentrality.setup_class, TestBipartiteCentrality.test_betweenness_centrality, TestBipartiteCentrality.test_bipartite_closeness_centrality_unconnected, TestBipartiteCentrality.test_closeness_centrality, TestBipartiteCentrality.test_davis_betweenness_centrality, TestBipartiteCentrality.test_davis_closeness_centrality; module: test_centrality
**test_cluster.py** — function: test_average_path_graph, test_bad_mode, test_not_bipartite, test_pairwise_bipartite_cc_functions, test_path_graph, test_ra_clustering_davis; 6 imports; module: test_cluster
**test_covering.py** — class: TestMinEdgeCover; 2 imports; method: TestMinEdgeCover.test_bipartite_default, TestMinEdgeCover.test_bipartite_explicit, TestMinEdgeCover.test_empty_graph, TestMinEdgeCover.test_graph_single_edge; module: test_covering
**test_edgelist.py** — class: TestEdgelist; function: test_bipartite_edgelist_consistent_strip_handling; 7 imports; method: TestEdgelist.setup_class, TestEdgelist.test_edgelist_graph, TestEdgelist.test_edgelist_integers, TestEdgelist.test_edgelist_multigraph, TestEdgelist.test_empty_digraph, TestEdgelist.test_latin1; module: test_edgelist
**test_extendability.py** — function: test_cubical_graph_is_2, test_disconnected_raises, test_k_is_3, test_k_is_4, test_k_is_5, test_k_is_6; 2 imports; module: test_extendability
**test_generators.py** — class: TestGeneratorsBipartite; 11 imports; method: TestGeneratorsBipartite.test_alternating_havel_hakimi_graph, TestGeneratorsBipartite.test_complete_bipartite_graph, TestGeneratorsBipartite.test_complete_bipartite_graph_str, TestGeneratorsBipartite.test_configuration_model, TestGeneratorsBipartite.test_gnmk_random_graph, TestGeneratorsBipartite.test_gnmk_random_graph_complete; module: test_generators
**test_link_analysis.py** — class: TestBipartiteLinkAnalysis; 4 imports; method: TestBipartiteLinkAnalysis.setup_class, TestBipartiteLinkAnalysis.test_birank_empty_bipartite_set, TestBipartiteLinkAnalysis.test_birank_invalid_alpha_beta, TestBipartiteLinkAnalysis.test_birank_power_iteration_failed_convergence, TestBipartiteLinkAnalysis.test_collaborative_filtering_birank, TestBipartiteLinkAnalysis.test_davis_birank; module: test_link_analysis
**test_matching.py** — class: TestMatching, TestMinimumWeightFullMatching; function: test_eppstein_matching; 8 imports; method: TestMatching.check_match, TestMatching.check_vertex_cover, TestMatching.setup_method, TestMatching.test_eppstein_matching, TestMatching.test_eppstein_matching_disconnected, TestMatching.test_eppstein_matching_simple; module: test_matching
**test_matrix.py** — class: TestBiadjacencyMatrix; 5 imports; method: TestBiadjacencyMatrix.test_biadjacency_matrix, TestBiadjacencyMatrix.test_biadjacency_matrix_empty_graph, TestBiadjacencyMatrix.test_biadjacency_matrix_order, TestBiadjacencyMatrix.test_biadjacency_matrix_weight, TestBiadjacencyMatrix.test_duplicate_col, TestBiadjacencyMatrix.test_duplicate_row; module: test_matrix
**test_project.py** — class: TestBipartiteProject, TestBipartiteWeightedProjection; 5 imports; method: TestBipartiteProject.test_digraph_weighted_projection, TestBipartiteProject.test_directed_path_collaboration_projected_graph, TestBipartiteProject.test_directed_projection, TestBipartiteProject.test_path_collaboration_projected_graph, TestBipartiteProject.test_path_projected_graph, TestBipartiteProject.test_path_projected_properties_graph; module: test_project
**test_redundancy.py** — function: test_no_redundant_nodes, test_not_enough_neighbors, test_redundant_nodes; 5 imports; module: test_redundancy
**test_spectral_bipartivity.py** — class: TestSpectralBipartivity; 3 imports; method: TestSpectralBipartivity.test_k23_like, TestSpectralBipartivity.test_single_nodes, TestSpectralBipartivity.test_star_like; module: test_spectral_bipartivity
**boundary.py** — function: edge_boundary, node_boundary; 2 imports; module: boundary
**bridges.py** — function: bridges, has_bridges, local_bridges; 3 imports; module: bridges
**broadcasting.py** — function: _get_broadcast_centers, _get_max_broadcast_value, tree_broadcast_center, tree_broadcast_time; 2 imports; module: broadcasting
**__init__.py** — 20 imports; module: __init__
**betweenness.py** — function: _accumulate_basic, _accumulate_edges, _accumulate_endpoints, _add_edge_keys, _rescale, _single_source_dijkstra_path_basic; 9 imports; module: betweenness
**betweenness_subset.py** — function: _accumulate_edges_subset, _accumulate_subset, betweenness_centrality_subset, edge_betweenness_centrality_subset; 5 imports; module: betweenness_subset
**closeness.py** — function: closeness_centrality, incremental_closeness_centrality; 4 imports; module: closeness
**current_flow_betweenness.py** — function: approximate_current_flow_betweenness_centrality, current_flow_betweenness_centrality, edge_current_flow_betweenness_centrality; 9 imports; module: current_flow_betweenness
**current_flow_betweenness_subset.py** — function: current_flow_betweenness_centrality_subset, edge_current_flow_betweenness_centrality_subset; 5 imports; module: current_flow_betweenness_subset
**current_flow_closeness.py** — function: current_flow_closeness_centrality; 6 imports; module: current_flow_closeness
**degree_alg.py** — function: degree_centrality, in_degree_centrality, out_degree_centrality; 2 imports; module: degree_alg
**dispersion.py** — function: dispersion; 2 imports; module: dispersion
**eigenvector.py** — function: eigenvector_centrality, eigenvector_centrality_numpy; 5 imports; module: eigenvector
**flow_matrix.py** — class: CGInverseLaplacian, FullInverseLaplacian, InverseLaplacian, SuperLUInverseLaplacian; function: flow_matrix_row; 3 imports; method: CGInverseLaplacian.init_solver, CGInverseLaplacian.solve, CGInverseLaplacian.solve_inverse, FullInverseLaplacian.init_solver, FullInverseLaplacian.solve, FullInverseLaplacian.solve_inverse; module: flow_matrix
**group.py** — function: _dfbnb, _group_preprocessing, _heuristic, group_betweenness_centrality, group_closeness_centrality, group_degree_centrality; 8 imports; module: group
**harmonic.py** — function: harmonic_centrality; 2 imports; module: harmonic
**katz.py** — function: katz_centrality, katz_centrality_numpy; 4 imports; module: katz
**laplacian.py** — function: laplacian_centrality; 3 imports; module: laplacian
**load.py** — function: _edge_betweenness, _node_betweenness, edge_load_centrality, newman_betweenness_centrality; 2 imports; module: load
**percolation.py** — function: _accumulate_percolation, percolation_centrality; 3 imports; module: percolation
**reaching.py** — function: _average_weight, global_reaching_centrality, local_reaching_centrality; 2 imports; module: reaching
**second_order.py** — function: second_order_centrality; 3 imports; module: second_order
**subgraph_alg.py** — function: communicability_betweenness_centrality, estrada_index, subgraph_centrality, subgraph_centrality_exp; 4 imports; module: subgraph_alg
**test_betweenness_centrality.py** — class: TestBetweennessCentrality, TestEdgeBetweennessCentrality, TestWeightedBetweennessCentrality, TestWeightedEdgeBetweennessCentrality; function: weighted_G; 3 imports; method: TestBetweennessCentrality.test_K5, TestBetweennessCentrality.test_K5_endpoints, TestBetweennessCentrality.test_P3, TestBetweennessCentrality.test_P3_endpoints, TestBetweennessCentrality.test_P3_normalized, TestBetweennessCentrality.test_directed_path; module: test_betweenness_centrality
**test_betweenness_centrality_subset.py** — class: TestEdgeSubsetBetweennessCentrality, TestSubsetBetweennessCentrality; function: test_equivalence_non_subset; 2 imports; method: TestEdgeSubsetBetweennessCentrality.test_K5, TestEdgeSubsetBetweennessCentrality.test_P5, TestEdgeSubsetBetweennessCentrality.test_P5_directed, TestEdgeSubsetBetweennessCentrality.test_P5_multiple_target, TestEdgeSubsetBetweennessCentrality.test_box, TestEdgeSubsetBetweennessCentrality.test_box_and_path; module: test_betweenness_centrality_subset
**test_closeness_centrality.py** — class: TestClosenessCentrality, TestIncrementalClosenessCentrality; function: undirected_G; 2 imports; method: TestClosenessCentrality.test_digraph, TestClosenessCentrality.test_florentine_families_closeness, TestClosenessCentrality.test_k5_closeness, TestClosenessCentrality.test_krackhardt_closeness, TestClosenessCentrality.test_les_miserables_closeness, TestClosenessCentrality.test_p3_closeness; module: test_closeness_centrality
**test_current_flow_betweenness_centrality.py** — class: TestApproximateFlowBetweennessCentrality, TestEdgeFlowBetweennessCentrality, TestFlowBetweennessCentrality, TestWeightedFlowBetweennessCentrality; function: test_unconnected_graphs_betweenness_centrality; 4 imports; method: TestApproximateFlowBetweennessCentrality.test_K4, TestApproximateFlowBetweennessCentrality.test_K4_normalized, TestApproximateFlowBetweennessCentrality.test_epsilon_validation, TestApproximateFlowBetweennessCentrality.test_grid, TestApproximateFlowBetweennessCentrality.test_lower_kmax, TestApproximateFlowBetweennessCentrality.test_normalization_edge_case_small_graph; module: test_current_flow_betweenness_centrality
**test_current_flow_betweenness_centrality_subset.py** — class: TestEdgeFlowBetweennessCentrality, TestFlowBetweennessCentrality; 4 imports; method: TestEdgeFlowBetweennessCentrality.test_C4, TestEdgeFlowBetweennessCentrality.test_K4, TestEdgeFlowBetweennessCentrality.test_K4_normalized, TestEdgeFlowBetweennessCentrality.test_P4, TestFlowBetweennessCentrality.test_K4, TestFlowBetweennessCentrality.test_K4_normalized; module: test_current_flow_betweenness_centrality_subset
**test_current_flow_closeness.py** — class: TestFlowClosenessCentrality, TestWeightedFlowClosenessCentrality; 2 imports; method: TestFlowClosenessCentrality.test_K4, TestFlowClosenessCentrality.test_P4, TestFlowClosenessCentrality.test_current_flow_closeness_centrality_not_connected, TestFlowClosenessCentrality.test_star; module: test_current_flow_closeness
**test_degree_centrality.py** — class: TestDegreeCentrality; 2 imports; method: TestDegreeCentrality.setup_method, TestDegreeCentrality.test_degree_centrality_1, TestDegreeCentrality.test_degree_centrality_2, TestDegreeCentrality.test_degree_centrality_3, TestDegreeCentrality.test_degree_centrality_4, TestDegreeCentrality.test_indegree_centrality; module: test_degree_centrality
**test_dispersion.py** — class: TestDispersion; function: small_ego_G; 1 imports; method: TestDispersion.test_article, TestDispersion.test_dispersion_v_only, TestDispersion.test_impossible_things, TestDispersion.test_results_length; module: test_dispersion
**test_eigenvector_centrality.py** — class: TestEigenvectorCentrality, TestEigenvectorCentralityDirected, TestEigenvectorCentralityExceptions; 3 imports; method: TestEigenvectorCentrality.test_K5, TestEigenvectorCentrality.test_P3, TestEigenvectorCentrality.test_P3_unweighted, TestEigenvectorCentrality.test_maxiter, TestEigenvectorCentralityDirected.setup_class, TestEigenvectorCentralityDirected.test_eigenvector_centrality_unweighted; module: test_eigenvector_centrality
**test_group.py** — class: TestGroupBetweennessCentrality, TestGroupClosenessCentrality, TestGroupDegreeCentrality, TestProminentGroup; 2 imports; method: TestGroupBetweennessCentrality.test_group_betweenness_directed_weighted, TestGroupBetweennessCentrality.test_group_betweenness_disconnected_graph, TestGroupBetweennessCentrality.test_group_betweenness_node_not_in_graph, TestGroupBetweennessCentrality.test_group_betweenness_normalized, TestGroupBetweennessCentrality.test_group_betweenness_single_node, TestGroupBetweennessCentrality.test_group_betweenness_value_zero; module: test_group
**test_harmonic_centrality.py** — class: TestClosenessCentrality; 3 imports; method: TestClosenessCentrality.setup_class, TestClosenessCentrality.test_bal_tree, TestClosenessCentrality.test_clique_complete, TestClosenessCentrality.test_cycle_C4, TestClosenessCentrality.test_cycle_C5, TestClosenessCentrality.test_cycle_c4_directed; module: test_harmonic_centrality
**test_katz_centrality.py** — class: TestKatzCentrality, TestKatzCentralityDirected, TestKatzCentralityDirectedNumpy, TestKatzCentralityNumpy, TestKatzEigenvectorVKatz; 3 imports; method: TestKatzCentrality.test_K5, TestKatzCentrality.test_P3, TestKatzCentrality.test_bad_beta, TestKatzCentrality.test_bad_beta_number, TestKatzCentrality.test_beta_as_dict, TestKatzCentrality.test_beta_as_scalar; module: test_katz_centrality
**test_laplacian_centrality.py** — function: test_laplacian_centrality_DG, test_laplacian_centrality_E, test_laplacian_centrality_FF, test_laplacian_centrality_K, test_laplacian_centrality_K5, test_laplacian_centrality_KC; 2 imports; module: test_laplacian_centrality
**test_load_centrality.py** — class: TestLoadCentrality; 2 imports; method: TestLoadCentrality.setup_class, TestLoadCentrality.test_P2_normalized_load, TestLoadCentrality.test_c4_edge_load, TestLoadCentrality.test_florentine_families_load, TestLoadCentrality.test_k5_edge_load, TestLoadCentrality.test_k5_load; module: test_load_centrality
**test_percolation_centrality.py** — function: example1a_G, example1b_G, test_converge_to_betweenness, test_default_percolation, test_percolation_example1a, test_percolation_example1b; 2 imports; module: test_percolation_centrality
**test_reaching.py** — class: TestGlobalReachingCentrality, TestLocalReachingCentrality; 2 imports; method: TestGlobalReachingCentrality.test_cycle_directed_unweighted, TestGlobalReachingCentrality.test_cycle_directed_weighted, TestGlobalReachingCentrality.test_cycle_undirected_unweighted, TestGlobalReachingCentrality.test_cycle_undirected_weighted, TestGlobalReachingCentrality.test_directed_star, TestGlobalReachingCentrality.test_directed_weighted; module: test_reaching
**test_second_order_centrality.py** — function: test_K3, test_P3, test_empty, test_non_connected, test_non_negative_edge_weights, test_one_node_graph; 2 imports; module: test_second_order_centrality
**test_subgraph.py** — class: TestSubgraph; 6 imports; method: TestSubgraph.test_communicability_betweenness_centrality, TestSubgraph.test_communicability_betweenness_centrality_small, TestSubgraph.test_estrada_index, TestSubgraph.test_subgraph_centrality, TestSubgraph.test_subgraph_centrality_big_graph; module: test_subgraph
**test_trophic.py** — function: test_no_basal_node, test_trophic_differences, test_trophic_incoherence_parameter_cannibalism, test_trophic_incoherence_parameter_no_cannibalism, test_trophic_levels, test_trophic_levels_even_more_complex; 2 imports; module: test_trophic
**test_voterank.py** — class: TestVoteRankCentrality; 1 imports; method: TestVoteRankCentrality.test_voterank_centrality_1, TestVoteRankCentrality.test_voterank_centrality_2, TestVoteRankCentrality.test_voterank_centrality_3, TestVoteRankCentrality.test_voterank_centrality_4, TestVoteRankCentrality.test_voterank_centrality_5, TestVoteRankCentrality.test_voterank_emptygraph; module: test_voterank
**trophic.py** — function: trophic_differences, trophic_incoherence_parameter, trophic_levels; 3 imports; module: trophic
**voterank_alg.py** — function: voterank; 1 imports; module: voterank_alg
**chains.py** — function: chain_decomposition; 2 imports; module: chains
**chordal.py** — class: NetworkXTreewidthBoundExceeded; function: _find_chordality_breaker, _find_missing_edge, _is_complete_graph, _max_cardinality_node, chordal_graph_cliques, chordal_graph_treewidth; 5 imports; module: chordal
**clique.py** — class: MaxWeightClique; function: enumerate_all_cliques, find_cliques, find_cliques_recursive, make_clique_bipartite, make_max_clique_graph, max_weight_clique; 8 imports; method: MaxWeightClique.__init__, MaxWeightClique.expand, MaxWeightClique.find_branching_nodes, MaxWeightClique.find_max_weight_clique, MaxWeightClique.greedily_find_independent_set, MaxWeightClique.update_incumbent_if_improved; module: clique
**cluster.py** — function: _directed_triangles_and_degree_iter, _directed_weighted_triangles_and_degree_iter, _triangles_and_degree_iter, _weighted_triangles_and_degree_iter, all_triangles, average_clustering; 6 imports; module: cluster
**__init__.py** — 2 imports; module: __init__
**equitable_coloring.py** — function: change_color, equitable_color, is_coloring, is_equitable, make_C_from_F, make_H_from_C_N; 2 imports; module: equitable_coloring; rationale: [NOTE] Departing from the paper here., [TODO] Checking whether a color has been visited can be made faster by
**greedy_coloring.py** — class: _AdjEntry, _Node; function: _greedy_coloring_with_interchange, _maximal_independent_set, greedy_color, strategy_connected_sequential, strategy_connected_sequential_bfs, strategy_connected_sequential_dfs; 6 imports; method: _AdjEntry.__init__, _AdjEntry.__repr__, _Node.__init__, _Node.__repr__, _Node.assign_color, _Node.clear_color; module: greedy_coloring
**test_coloring.py** — class: TestColoring; function: check_state, cs_shc, dict_to_sets, disconnected, empty_graph, gis_hc; 3 imports; method: TestColoring.test_bad_inputs, TestColoring.test_basic_cases, TestColoring.test_case_V_plus_not_in_A_cal, TestColoring.test_cast_no_solo, TestColoring.test_equitable_color, TestColoring.test_equitable_color_empty; module: test_coloring
**communicability_alg.py** — function: communicability, communicability_exp; 4 imports; module: communicability_alg
**__init__.py** — 13 imports; module: __init__
**asyn_fluid.py** — function: asyn_fluidc; 7 imports; module: asyn_fluid
**bipartitions.py** — function: _kernighan_lin_sweep, greedy_node_swap_bipartition, kernighan_lin_bisection, spectral_modularity_bipartition; 5 imports; module: bipartitions
**centrality.py** — function: _without_most_central_edges, girvan_newman; 1 imports; module: centrality
**community_utils.py** — function: is_partition; 1 imports; module: community_utils
**divisive.py** — function: edge_betweenness_partition, edge_current_flow_betweenness_partition; 2 imports; module: divisive
**kclique.py** — function: _get_adjacent_cliques, k_clique_communities; 2 imports; module: kclique
**label_propagation.py** — function: _color_network, _fast_label_count, _labeling_complete, _most_frequent_labels, _update_label, asyn_lpa_communities; 7 imports; module: label_propagation
**leiden.py** — function: leiden_communities, leiden_partitions; 5 imports; module: leiden
**local.py** — function: _calculate_local_modularity_for_candidate, _clauset_greedy_source_expansion, greedy_source_expansion; module: local
**louvain.py** — function: _convert_multigraph, _gen_graph, _neighbor_weights, _one_level, louvain_communities, louvain_partitions; 6 imports; module: louvain
**lukes.py** — function: _split_n_from, lukes_partitioning; 5 imports; module: lukes
**modularity_max.py** — function: _greedy_modularity_communities_generator, greedy_modularity_communities, naive_greedy_modularity_communities; 6 imports; module: modularity_max
**quality.py** — class: NotAPartition; function: _require_partition, inter_community_edges, inter_community_non_edges, intra_community_edges, modularity, partition_quality; 5 imports; method: NotAPartition.__init__; module: quality
**test_asyn_fluid.py** — function: test_asyn_fluidc_max_iter, test_exceptions, test_five_clique_ring, test_raises_on_directed_and_multigraphs, test_single_node, test_two_clique_communities; 5 imports; module: test_asyn_fluid
**test_bipartitions.py** — function: assert_partition_equal, test_greedy_bipartition, test_greedy_multigraph_disallowed, test_greedy_node_swap_too_many_blocks, test_greedy_non_disjoint_partition, test_karate_club; 5 imports; module: test_bipartitions
**test_centrality.py** — class: TestGirvanNewman; function: set_of_sets, validate_communities, validate_possible_communities; 2 imports; method: TestGirvanNewman.test_directed, TestGirvanNewman.test_most_valuable_edge, TestGirvanNewman.test_no_edges, TestGirvanNewman.test_selfloops, TestGirvanNewman.test_undirected; module: test_centrality
**test_divisive.py** — function: test_edge_betweenness_partition, test_edge_current_flow_betweenness_partition; 2 imports; module: test_divisive
**test_kclique.py** — class: TestZacharyKarateClub; function: test_bad_k, test_isolated_K5, test_overlapping_K5; 3 imports; method: TestZacharyKarateClub._check_communities, TestZacharyKarateClub.setup_method, TestZacharyKarateClub.test_k2, TestZacharyKarateClub.test_k3, TestZacharyKarateClub.test_k4, TestZacharyKarateClub.test_k5; module: test_kclique
**test_label_propagation.py** — class: TestAsynLpaCommunities, TestFastLabelPropagationCommunities; function: test_connected_communities, test_directed_not_supported, test_iterator_vs_iterable, test_one_node, test_termination, test_unconnected_communities; 4 imports; method: TestAsynLpaCommunities._check_communities, TestAsynLpaCommunities.test_null_graph, TestAsynLpaCommunities.test_seed_argument, TestAsynLpaCommunities.test_several_communities, TestAsynLpaCommunities.test_simple_communities, TestAsynLpaCommunities.test_single_node; module: test_label_propagation
**test_leiden.py** — function: test_directed_not_implemented, test_empty_graph, test_leiden_with_nx_backend, test_max_level, test_modularity_increase, test_none_weight_param; 4 imports; module: test_leiden
**test_local.py** — function: test_greedy_source_expansion_connected_component, test_greedy_source_expansion_cutoff, test_greedy_source_expansion_directed_graph, test_greedy_source_expansion_empty_graph, test_greedy_source_expansion_invalid_method, test_greedy_source_expansion_karate_club; 2 imports; module: test_local
**test_louvain.py** — function: test_directed_partition, test_directed_selfloops, test_empty_graph, test_karate_club_partition, test_max_level, test_modularity_increase; 2 imports; module: test_louvain
**test_lukes.py** — function: paper_1_case, paper_2_case, test_mandatory_integrality, test_mandatory_tree, test_paper_1_case, test_paper_2_case; 3 imports; module: test_lukes
**test_modularity_max.py** — function: test_best_n, test_cutoff_parameter, test_greed_modularity_communities_multidigraph, test_greed_modularity_communities_multidigraph_weighted, test_greedy_modularity_communities_components, test_greedy_modularity_communities_corner_cases; 4 imports; module: test_modularity_max
**test_quality.py** — class: TestCoverage, TestPerformance; function: test_inter_community_edges_with_digraphs, test_modularity, test_modularity_resolution; 6 imports; method: TestCoverage.test_bad_partition, TestCoverage.test_good_partition, TestPerformance.test_bad_partition, TestPerformance.test_good_partition; module: test_quality
**test_utils.py** — function: test_is_partition, test_not_covering, test_not_disjoint, test_not_node; 1 imports; module: test_utils
**__init__.py** — 6 imports; module: __init__
**attracting.py** — function: attracting_components, is_attracting_component, number_attracting_components; 2 imports; module: attracting
**biconnected.py** — function: _biconnected_dfs, articulation_points, biconnected_component_edges, biconnected_components, is_biconnected; 3 imports; module: biconnected
**connected.py** — function: _plain_bfs, connected_components, is_connected, node_connected_component, number_connected_components; 3 imports; module: connected
**semiconnected.py** — function: is_semiconnected; 3 imports; module: semiconnected
**strongly_connected.py** — function: condensation, is_strongly_connected, kosaraju_strongly_connected_components, number_strongly_connected_components, strongly_connected_components; 2 imports; module: strongly_connected
**test_attracting.py** — class: TestAttractingComponents; 3 imports; method: TestAttractingComponents.setup_class, TestAttractingComponents.test_attracting_components, TestAttractingComponents.test_connected_raise, TestAttractingComponents.test_is_attracting_component, TestAttractingComponents.test_number_attacting_components; module: test_attracting
**test_biconnected.py** — function: assert_components_edges_equal, assert_components_equal, test_articulation_points_cycle, test_articulation_points_repetitions, test_barbell, test_biconnected_components1; 3 imports; module: test_biconnected
**test_connected.py** — class: TestConnected; 5 imports; method: TestConnected.setup_class, TestConnected.test_connected_components, TestConnected.test_connected_components2, TestConnected.test_connected_components_nx_loopback, TestConnected.test_connected_mutability, TestConnected.test_connected_raise; module: test_connected
**test_semiconnected.py** — class: TestIsSemiconnected; 3 imports; method: TestIsSemiconnected.test_alternating_path, TestIsSemiconnected.test_cycle, TestIsSemiconnected.test_dumbbell, TestIsSemiconnected.test_empty, TestIsSemiconnected.test_path, TestIsSemiconnected.test_single_node_graph; module: test_semiconnected
**test_strongly_connected.py** — class: TestStronglyConnected; 3 imports; method: TestStronglyConnected.setup_class, TestStronglyConnected.test_condensation_mapping_and_members, TestStronglyConnected.test_connected_mutability, TestStronglyConnected.test_connected_raise, TestStronglyConnected.test_contract_scc1, TestStronglyConnected.test_contract_scc_edge; module: test_strongly_connected
**test_weakly_connected.py** — class: TestWeaklyConnected; function: test_is_weakly_connected_empty_graph_raises; 3 imports; method: TestWeaklyConnected.setup_class, TestWeaklyConnected.test_connected_mutability, TestWeaklyConnected.test_connected_raise, TestWeaklyConnected.test_is_weakly_connected, TestWeaklyConnected.test_null_graph, TestWeaklyConnected.test_number_weakly_connected_components; module: test_weakly_connected
**weakly_connected.py** — function: _plain_bfs, is_weakly_connected, number_weakly_connected_components, weakly_connected_components; 2 imports; module: weakly_connected
**__init__.py** — 9 imports; module: __init__
**connectivity.py** — function: all_pairs_node_connectivity, average_node_connectivity, edge_connectivity, local_edge_connectivity, local_node_connectivity, node_connectivity; 11 imports; module: connectivity
**cuts.py** — function: minimum_edge_cut, minimum_node_cut, minimum_st_edge_cut, minimum_st_node_cut; 6 imports; module: cuts
**disjoint_paths.py** — function: _unique_everseen, edge_disjoint_paths, node_disjoint_paths; 8 imports; module: disjoint_paths
**edge_augmentation.py** — function: _compat_shuffle, _lightest_meta_edges, _minimum_rooted_branching, _ordered, _unpack_available_edges, bridge_augmentation; 7 imports; module: edge_augmentation
**edge_kcomponents.py** — class: EdgeComponentAuxGraph; function: _high_degree_components, _k_edge_subgraphs_nodes, _low_degree_nodes, bridge_components, general_k_edge_subgraphs, k_edge_components; 5 imports; method: EdgeComponentAuxGraph.construct, EdgeComponentAuxGraph.k_edge_components, EdgeComponentAuxGraph.k_edge_subgraphs; module: edge_kcomponents; rationale: [NOTE] remaining connected components may not be k-edge-connected, [TODO] fix decor for classmethods, [TODO] investigate https://arxiv.org/abs/1412.6466 for k=2
**kcomponents.py** — function: _consolidate, _generate_partition, _reconstruct_k_components, build_k_number_dict, k_components; 6 imports; module: kcomponents
**kcutsets.py** — function: _is_separating_set, all_node_cuts; 9 imports; module: kcutsets
**stoerwagner.py** — function: stoer_wagner; 5 imports; module: stoerwagner
**test_connectivity.py** — class: TestAllPairsNodeConnectivity; function: _generate_no_biconnected, test_articulation_points, test_average_connectivity, test_average_connectivity_directed, test_brandes_erlebach, test_complete_graphs; 6 imports; method: TestAllPairsNodeConnectivity.setup_class, TestAllPairsNodeConnectivity.test_all_pairs_connectivity, TestAllPairsNodeConnectivity.test_all_pairs_connectivity_directed, TestAllPairsNodeConnectivity.test_all_pairs_connectivity_icosahedral, TestAllPairsNodeConnectivity.test_all_pairs_connectivity_nbunch, TestAllPairsNodeConnectivity.test_all_pairs_connectivity_nbunch_combinations; module: test_connectivity
**test_cuts.py** — function: _generate_no_biconnected, test_articulation_points, test_brandes_erlebach_book, test_edge_cutset_random_graphs, test_empty_graphs, test_icosahedral_cutset; 6 imports; module: test_cuts
**test_disjoint_paths.py** — function: are_edge_disjoint_paths, are_node_disjoint_paths, is_path, test_cutoff_disjoint_paths, test_florentine_families, test_graph_from_pr_2053; 4 imports; module: test_disjoint_paths
**test_edge_augmentation.py** — function: _assert_solution_properties, _augment_and_check, _check_augmentations, _check_unconstrained_bridge_property, tarjan_bridge_graph, test_barbell; 12 imports; module: test_edge_augmentation
**test_edge_kcomponents.py** — function: _all_pairs_connectivity, _assert_local_cc_edge_connectivity, _assert_subgraph_edge_connectivity, _check_edge_connectivity, _memo_connectivity, fset; 7 imports; module: test_edge_kcomponents
**test_kcomponents.py** — function: _check_connectivity, test_configuration, test_davis_southern_women, test_davis_southern_women_detail_3_and_4, test_directed, test_empty_k_components; 5 imports; module: test_kcomponents
**test_kcutsets.py** — function: _check_separating_sets, _generate_no_biconnected, graph_example_1, test_all_node_cuts_sap, test_all_node_cuts_simple_case, test_alternative_flow_functions; 5 imports; module: test_kcutsets
**test_stoer_wagner.py** — function: _check_partition, _test_stoer_wagner, test_exceptions, test_graph1, test_graph2, test_graph3; 3 imports; module: test_stoer_wagner
**utils.py** — function: build_auxiliary_edge_connectivity, build_auxiliary_node_connectivity; 1 imports; module: utils
**core.py** — function: _core_subgraph, core_number, k_core, k_corona, k_crust, k_shell; 1 imports; module: core
**covering.py** — function: is_edge_cover, min_edge_cover; 5 imports; module: covering
**cuts.py** — function: boundary_expansion, conductance, cut_size, edge_expansion, mixing_expansion, node_expansion; 2 imports; module: cuts
**cycles.py** — class: _NeighborhoodCache; function: _bounded_cycle_search, _chordless_cycle_search, _directed_cycle_search, _johnson_cycle_search, _min_cycle, _min_cycle_basis; 7 imports; method: _NeighborhoodCache.__init__, _NeighborhoodCache.__missing__; module: cycles; rationale: [NOTE] Use "Gi_weight" for name of weight attribute, [TODO] use set for speedup?
**d_separation.py** — function: _reachable, find_minimal_d_separator, is_d_separator, is_minimal_d_separator; 5 imports; module: d_separation
**dag.py** — function: all_topological_sorts, ancestors, antichains, colliders, dag_longest_path, dag_longest_path_length; 12 imports; module: dag; rationale: [NOTE] it is important to iterate over edges instead, [NOTE] it is important to iterate over edges instead
**distance_measures.py** — function: _extrema_bounding, barycenter, center, diameter, eccentricity, effective_graph_resistance; 5 imports; module: distance_measures
**distance_regular.py** — function: global_parameters, intersection_array, is_distance_regular, is_strongly_regular; 6 imports; module: distance_regular
**dominance.py** — function: dominance_frontiers, immediate_dominators; 3 imports; module: dominance
**dominating.py** — function: connected_dominating_set, dominating_set, is_connected_dominating_set, is_dominating_set; 6 imports; module: dominating
**efficiency_measures.py** — function: efficiency, global_efficiency, local_efficiency; 3 imports; module: efficiency_measures
**euler.py** — function: _find_path_start, _multigraph_eulerian_circuit, _simplegraph_eulerian_circuit, eulerian_circuit, eulerian_path, eulerize; 4 imports; module: euler
**__init__.py** — 12 imports; module: __init__
**boykovkolmogorov.py** — function: boykov_kolmogorov, boykov_kolmogorov_impl; 4 imports; module: boykovkolmogorov
**capacityscaling.py** — function: _build_flow_dict, _build_residual_network, _detect_unboundedness, capacity_scaling; 6 imports; module: capacityscaling
**dinitz_alg.py** — function: dinitz, dinitz_impl; 4 imports; module: dinitz_alg
**edmondskarp.py** — function: edmonds_karp, edmonds_karp_core, edmonds_karp_impl; 2 imports; module: edmondskarp
**gomory_hu.py** — function: gomory_hu_tree; 4 imports; module: gomory_hu
**maxflow.py** — function: maximum_flow, maximum_flow_value, minimum_cut, minimum_cut_value; 7 imports; module: maxflow
**mincost.py** — function: cost_of_flow, max_flow_min_cost, min_cost_flow, min_cost_flow_cost; 1 imports; module: mincost
**networksimplex.py** — class: _DataEssentialsAndFunctions; function: network_simplex; 7 imports; method: _DataEssentialsAndFunctions.__init__, _DataEssentialsAndFunctions.add_edge, _DataEssentialsAndFunctions.augment_flow, _DataEssentialsAndFunctions.find_apex, _DataEssentialsAndFunctions.find_cycle, _DataEssentialsAndFunctions.find_entering_edges; module: networksimplex
**preflowpush.py** — function: preflow_push, preflow_push_impl; 9 imports; module: preflowpush
**shortestaugmentingpath.py** — function: shortest_augmenting_path, shortest_augmenting_path_impl; 5 imports; module: shortestaugmentingpath
**test_gomory_hu.py** — class: TestGomoryHuTree; 8 imports; method: TestGomoryHuTree.compute_cutset, TestGomoryHuTree.minimum_edge_weight, TestGomoryHuTree.test_davis_southern_women_graph, TestGomoryHuTree.test_default_flow_function_karate_club_graph, TestGomoryHuTree.test_directed_raises, TestGomoryHuTree.test_empty_raises; module: test_gomory_hu
**test_maxflow.py** — class: TestCutoff, TestMaxFlowMinCutInterface, TestMaxflowMinCutCommon; function: compare_flows_and_cuts, compute_cutset, test_preflow_push_global_relabel_freq, test_preflow_push_makes_enough_space, test_shortest_augmenting_path_two_phase, validate_cuts; 9 imports; method: TestCutoff.test_complete_graph_cutoff, TestCutoff.test_cutoff, TestMaxFlowMinCutInterface.setup_method, TestMaxFlowMinCutInterface.test_flow_func_not_callable, TestMaxFlowMinCutInterface.test_flow_func_parameters, TestMaxFlowMinCutInterface.test_kwargs; module: test_maxflow
**test_maxflow_large_graph.py** — class: TestMaxflowLargeGraph; function: gen_pyramid, read_graph, validate_flows; 12 imports; method: TestMaxflowLargeGraph.test_complete_graph, TestMaxflowLargeGraph.test_gl1, TestMaxflowLargeGraph.test_gw1, TestMaxflowLargeGraph.test_preflow_push_global_relabel, TestMaxflowLargeGraph.test_pyramid, TestMaxflowLargeGraph.test_wlm3; module: test_maxflow_large_graph
**test_mincost.py** — class: TestMinCostFlow; 5 imports; method: TestMinCostFlow.test_bone_shaped, TestMinCostFlow.test_deadend, TestMinCostFlow.test_digon, TestMinCostFlow.test_digraph1, TestMinCostFlow.test_digraph2, TestMinCostFlow.test_digraph3; module: test_mincost
**test_networksimplex.py** — function: faux_inf_example, get_flowcost_from_flowdict, simple_flow_graph, simple_no_flow_graph, test_bone_shaped, test_deadend; 5 imports; module: test_networksimplex
**utils.py** — class: CurrentEdge, GlobalRelabelThreshold, Level; function: build_flow_dict, build_residual_network, detect_unboundedness; 2 imports; method: CurrentEdge.__eq__, CurrentEdge.__init__, CurrentEdge._rewind, CurrentEdge.get, CurrentEdge.move_to_next, GlobalRelabelThreshold.__init__; module: utils
**graph_hashing.py** — function: _hash_label, _init_node_labels, _neighborhood_aggregate_directed, _neighborhood_aggregate_undirected, weisfeiler_lehman_graph_hash, weisfeiler_lehman_subgraph_hashes; 5 imports; module: graph_hashing
**graphical.py** — function: _basic_graphical_tests, is_digraphical, is_graphical, is_multigraphical, is_pseudographical, is_valid_degree_sequence_erdos_gallai; 2 imports; module: graphical
**hierarchy.py** — function: flow_hierarchy; 1 imports; module: hierarchy
**hybrid.py** — function: is_kl_connected, kl_connected_subgraph; 2 imports; module: hybrid
**isolate.py** — function: is_isolate, isolates, number_of_isolates; 1 imports; module: isolate
**__init__.py** — 7 imports; module: __init__
**ismags.py** — class: EdgeLookup, ISMAGS; function: are_all_equal, color_degree_by_node, make_partition, node_to_part_ID_dict; 6 imports; method: EdgeLookup.__getitem__, EdgeLookup.__init__, EdgeLookup.items, ISMAGS.__init__, ISMAGS._find_permutations, ISMAGS._get_color_degree_candidates; module: ismags; rationale: [NOTE] allow zero size parts in identity check, [NOTE] isinstance(G.edges(), OutEdgeDataView) is only true for multi(di)graph, [TODO] allow for precomputed partitions and colors, [TODO] remove these two if-checks when confident they never arise
**isomorph.py** — function: could_be_isomorphic, fast_could_be_isomorphic, fast_graph_could_be_isomorphic, faster_could_be_isomorphic, faster_graph_could_be_isomorphic, graph_could_be_isomorphic; 5 imports; module: isomorph
**isomorphvf2.py** — class: DiGMState, DiGraphMatcher, GMState, GraphMatcher; 2 imports; method: DiGMState.__init__, DiGMState.restore, DiGraphMatcher.__init__, DiGraphMatcher._is_directed_matcher, DiGraphMatcher.candidate_pairs_iter, DiGraphMatcher.initialize; module: isomorphvf2
**matchhelpers.py** — function: allclose, categorical_multiedge_match, categorical_node_match, copyfunc, generic_multiedge_match, generic_node_match; 3 imports; module: matchhelpers
**temporalisomorphvf2.py** — class: TimeRespectingDiGraphMatcher, TimeRespectingGraphMatcher; 3 imports; method: TimeRespectingDiGraphMatcher.__init__, TimeRespectingDiGraphMatcher.get_pred_dates, TimeRespectingDiGraphMatcher.get_succ_dates, TimeRespectingDiGraphMatcher.one_hop, TimeRespectingDiGraphMatcher.preds, TimeRespectingDiGraphMatcher.semantic_feasibility; module: temporalisomorphvf2
**test_ismags.py** — class: TestDiGraphISO, TestLargestCommonSubgraph, TestSelfIsomorphism, TestSubgraphIsomorphism, TestWikipediaExample; function: _matches_to_sets, is_isomorphic, test_noncomparable_nodes, test_selfloop, test_simple_edge_match, test_simple_node_and_edge_match; 4 imports; method: TestDiGraphISO.test_is_isomorphic, TestDiGraphISO.test_non_isomorphic_same_degree_sequence, TestDiGraphISO.test_wikipedia_graph, TestLargestCommonSubgraph.test_mcis, TestLargestCommonSubgraph.test_symmetry_mcis, TestSelfIsomorphism.test_self_isomorphism; module: test_ismags
**test_isomorphism.py** — class: TestIsomorph; function: test_could_be_isomorphic_combined_properties, test_could_be_isomorphic_individual_vs_combined_dt, test_graph_could_be_isomorphic_variants_deprecated; 4 imports; method: TestIsomorph.setup_class, TestIsomorph.test_could_be_isomorphic, TestIsomorph.test_fast_could_be_isomorphic, TestIsomorph.test_faster_could_be_isomorphic, TestIsomorph.test_is_isomorphic; module: test_isomorphism
**test_isomorphvf2.py** — class: TestAtlas, TestVF2GraphDB, TestWikipediaExample; function: test_isomorphism_iter1, test_isomorphism_iter2, test_matcher_raises, test_monomorphism_edge_match, test_monomorphism_iter1, test_multiedge; 7 imports; method: TestAtlas.setup_class, TestAtlas.test_graph_atlas, TestVF2GraphDB.create_graph, TestVF2GraphDB.test_graph, TestVF2GraphDB.test_subgraph, TestVF2GraphDB.test_subgraph_monomorphic; module: test_isomorphvf2; rationale: [NOTE] this shows need to recreate the matcher for each graph change
**test_match_helpers.py** — class: TestGenericMultiEdgeMatch; function: test_categorical_node_match; 3 imports; method: TestGenericMultiEdgeMatch.setup_method, TestGenericMultiEdgeMatch.test_generic_multiedge_match; module: test_match_helpers
**test_temporalisomorphvf2.py** — class: TestDiTimeRespectingGraphMatcher, TestTimeRespectingGraphMatcher; function: provide_g1_edgelist, put_same_datetime, put_same_time, put_sequence_time, put_time_config_0, put_time_config_1; 5 imports; method: TestDiTimeRespectingGraphMatcher.provide_g1_topology, TestDiTimeRespectingGraphMatcher.provide_g2_path_3edges, TestDiTimeRespectingGraphMatcher.test_attNameStrange_timdelta_zero_same_dates_returns_true, TestDiTimeRespectingGraphMatcher.test_timdelta_one_config0_returns_no_embeddings, TestDiTimeRespectingGraphMatcher.test_timdelta_one_config1_returns_one_embedding, TestDiTimeRespectingGraphMatcher.test_timdelta_one_config2_returns_two_embeddings; module: test_temporalisomorphvf2
**test_tree_isomorphism.py** — function: _check_isomorphism, test_hardcoded, test_input_not_tree, test_long_paths_graphs, test_rooted_tree_isomorphism_different_order, test_tree_isomorphic_all_non_isomorphic_trees_relabeled; 4 imports; module: test_tree_isomorphism; rationale: [NOTE] number of nonisomorphic_trees grows very rapidly - do not increase n, [NOTE] number of nonisomorphic_trees grows very rapidly - do not increase n
**test_vf2pp.py** — class: TestAllGraphTypesEdgeCases, TestDiGraphISOVF2pp, TestGraphISOVF2pp, TestMultiGraphISOVF2pp, TestPreCheck; function: test_isomorphvf2pp_multidigraphs; 6 imports; method: TestAllGraphTypesEdgeCases.test_both_graphs_empty, TestAllGraphTypesEdgeCases.test_first_graph_empty, TestAllGraphTypesEdgeCases.test_second_graph_empty, TestDiGraphISOVF2pp.test_non_isomorphic_same_degree_sequence, TestDiGraphISOVF2pp.test_wikipedia_graph, TestGraphISOVF2pp.test_custom_graph1_same_labels; module: test_vf2pp
**test_vf2pp_helpers.py** — class: TestDiGraphCandidateSelection, TestDiGraphISOFeasibility, TestDiGraphTinoutUpdating, TestGraphCandidateSelection, TestGraphISOFeasibility, TestGraphTinoutUpdating; 17 imports; method: TestDiGraphCandidateSelection.test_covered_neighbors_no_labels, TestDiGraphCandidateSelection.test_covered_neighbors_with_labels, TestDiGraphCandidateSelection.test_no_covered_neighbors_no_labels, TestDiGraphCandidateSelection.test_no_covered_neighbors_with_labels, TestDiGraphCandidateSelection.test_same_in_out_degrees_no_candidate, TestDiGraphISOFeasibility.test_const_covered_neighbors; module: test_vf2pp_helpers
**test_vf2userfunc.py** — class: TestMatch_DiGraph, TestMatch_Graph, TestMatch_MultiDiGraph, TestMatch_MultiGraph; function: test_simple, test_weightkey; 4 imports; method: TestMatch_DiGraph.setup_method, TestMatch_Graph.build, TestMatch_Graph.setup_method, TestMatch_Graph.test_color1, TestMatch_Graph.test_color2, TestMatch_Graph.test_colorsandweights1; module: test_vf2userfunc
**tree_isomorphism.py** — function: root_trees, rooted_tree_isomorphism, tree_isomorphism; 3 imports; module: tree_isomorphism
**vf2pp.py** — function: _consistent_PT, _cut_PT, _feasibility, _find_candidates, _find_candidates_Di, _initialize_parameters; 2 imports; module: vf2pp; rationale: [TODO] do we need Ti_tilde_in? What nodes does it have?, [TODO] make the 4th argument the degree of u
**vf2userfunc.py** — class: DiGraphMatcher, GraphMatcher, MultiDiGraphMatcher, MultiGraphMatcher; function: _semantic_feasibility; 1 imports; method: DiGraphMatcher.__init__, DiGraphMatcher.semantic_feasibility, GraphMatcher.__init__; module: vf2userfunc
**__init__.py** — 2 imports; module: __init__
**hits_alg.py** — function: _hits_numpy, _hits_python, _hits_scipy, hits; 3 imports; module: hits_alg
**pagerank_alg.py** — function: _pagerank_numpy, _pagerank_python, _pagerank_scipy, google_matrix, pagerank; 3 imports; module: pagerank_alg
**test_hits.py** — class: TestHITS; 5 imports; method: TestHITS.setup_class, TestHITS.test_empty, TestHITS.test_hits, TestHITS.test_hits_not_convergent, TestHITS.test_hits_numpy; module: test_hits
**test_pagerank.py** — class: TestPageRank, TestPageRankScipy; 7 imports; method: TestPageRank.setup_class, TestPageRank.test_dangling_matrix, TestPageRank.test_dangling_pagerank, TestPageRank.test_empty, TestPageRank.test_google_matrix, TestPageRank.test_incomplete_personalization; module: test_pagerank
**link_prediction.py** — function: _apply_prediction, _community, adamic_adar_index, cn_soundarajan_hopcroft, common_neighbor_centrality, jaccard_coefficient; 3 imports; module: link_prediction
**lowest_common_ancestors.py** — function: all_pairs_lowest_common_ancestor, lowest_common_ancestor, tree_all_pairs_lowest_common_ancestor; 8 imports; module: lowest_common_ancestors
**matching.py** — function: is_matching, is_maximal_matching, is_perfect_matching, matching_dict_to_set, max_weight_matching, maximal_matching; 4 imports; module: matching
**__init__.py** — 5 imports; module: __init__
**contraction.py** — function: _quotient_graph, contracted_edge, contracted_nodes, equivalence_classes, quotient_graph; 8 imports; module: contraction
**test_contraction.py** — function: test_barbell, test_barbell_plus, test_blockmodel, test_condensation_as_quotient, test_contract_loop_graph, test_contracted_nodes_multigraph; 5 imports; module: test_contraction
**mis.py** — function: maximal_independent_set; 3 imports; module: mis
**moral.py** — function: moral_graph; 3 imports; module: moral
**node_classification.py** — function: _get_label_info, harmonic_function, local_and_global_consistency; 3 imports; module: node_classification
**non_randomness.py** — function: non_randomness; 4 imports; module: non_randomness
**__init__.py** — 4 imports; module: __init__
**all.py** — function: compose_all, disjoint_union_all, intersection_all, union_all; 3 imports; module: all
**binary.py** — function: compose, difference, disjoint_union, full_join, intersection, symmetric_difference; 1 imports; module: binary
**product.py** — function: _dict_product, _directed_edges_cross_edges, _edges_cross_nodes, _edges_cross_nodes_and_nodes, _init_product_graph, _node_product; 3 imports; module: product
**test_all.py** — function: test_empty_compose_all, test_empty_disjoint_union, test_empty_intersection_all, test_empty_union, test_input_output, test_intersection_all; 3 imports; module: test_all
**test_binary.py** — function: test_compose_multigraph, test_difference, test_difference2, test_difference_attributes, test_difference_multigraph_attributes, test_difference_raise; 3 imports; module: test_binary
**test_product.py** — function: test_cartesian_product_classic, test_cartesian_product_multigraph, test_cartesian_product_null, test_cartesian_product_raises, test_cartesian_product_random, test_cartesian_product_size; 3 imports; module: test_product
**test_unary.py** — function: test_complement, test_complement_2, test_reverse1; 2 imports; module: test_unary
**unary.py** — function: complement, reverse; 1 imports; module: unary
**perfect_graph.py** — function: is_perfect_graph; 3 imports; module: perfect_graph
**planar_drawing.py** — function: combinatorial_embedding_to_pos, get_canonical_ordering, make_bi_connected, set_position, triangulate_embedding, triangulate_face; 2 imports; module: planar_drawing
**planarity.py** — class: ConflictPair, Interval, LRPlanarity, PlanarEmbedding; function: check_planarity, check_planarity_recursive, get_counterexample, get_counterexample_recursive, is_planar, top_of_stack; 3 imports; method: ConflictPair.__init__, ConflictPair.lowest, ConflictPair.swap, Interval.__init__, Interval.conflicting, Interval.copy; module: planarity; rationale: [NOTE] this sorting leads to non linear time, [NOTE] this sorting leads to non linear time
**polynomials.py** — function: chromatic_polynomial, tutte_polynomial; 4 imports; module: polynomials
**reciprocity.py** — function: _reciprocity_iter, overall_reciprocity, reciprocity; 3 imports; module: reciprocity
**regular.py** — function: is_k_regular, is_regular, k_factor; 2 imports; module: regular
**richclub.py** — function: _compute_rc, rich_club_coefficient; 3 imports; module: richclub
**__init__.py** — 5 imports; module: __init__
**astar.py** — function: astar_path, astar_path_length; 5 imports; module: astar
**dense.py** — function: floyd_warshall, floyd_warshall_numpy, floyd_warshall_predecessor_and_distance, reconstruct_path; 3 imports; module: dense
**generic.py** — function: _build_paths_from_predecessors, all_pairs_all_shortest_paths, all_shortest_paths, average_shortest_path_length, has_path, shortest_path; 1 imports; module: generic
**test_astar.py** — class: TestAStar; 3 imports; method: TestAStar.setup_class, TestAStar.test_astar_NetworkXNoPath, TestAStar.test_astar_NodeNotFound, TestAStar.test_astar_admissible_heuristic_with_cutoff, TestAStar.test_astar_cutoff, TestAStar.test_astar_cutoff2; module: test_astar
**test_dense.py** — class: TestFloyd; 2 imports; method: TestFloyd.setup_class, TestFloyd.test_cycle, TestFloyd.test_floyd_warshall_predecessor_and_distance, TestFloyd.test_reconstruct_path, TestFloyd.test_weight_parameter, TestFloyd.test_weighted; module: test_dense
**test_dense_numpy.py** — function: test_cycle_numpy, test_directed_cycle_numpy, test_nodelist, test_weight_parameter_numpy, test_weighted_numpy_three_edges, test_weighted_numpy_two_edges; 2 imports; module: test_dense_numpy
**test_generic.py** — class: TestAverageShortestPathLength, TestAverageShortestPathLengthNumpy, TestGenericPath; function: validate_grid_path; 3 imports; method: TestAverageShortestPathLength.test_bad_method, TestAverageShortestPathLength.test_cycle_graph, TestAverageShortestPathLength.test_directed_not_strongly_connected, TestAverageShortestPathLength.test_null_graph, TestAverageShortestPathLength.test_path_graph, TestAverageShortestPathLength.test_specified_methods; module: test_generic
**test_unweighted.py** — class: TestUnweightedPath; function: validate_grid_path; 3 imports; method: TestUnweightedPath.setup_class, TestUnweightedPath.test_all_pairs_shortest_path, TestUnweightedPath.test_all_pairs_shortest_path_length, TestUnweightedPath.test_bidirectional_shortest_path, TestUnweightedPath.test_bidirectional_shortest_path_src_tgt_not_in_graph, TestUnweightedPath.test_predecessor_cutoff; module: test_unweighted
**test_weighted.py** — class: TestBellmanFordAndGoldbergRadzik, TestDijkstraPathLength, TestJohnsonAlgorithm, TestMultiSourceDijkstra, TestWeightedPath, WeightedTestBase; function: validate_length_path, validate_path; 4 imports; method: TestBellmanFordAndGoldbergRadzik.test_4_cycle, TestBellmanFordAndGoldbergRadzik.test_absent_source_bellman_ford, TestBellmanFordAndGoldbergRadzik.test_absent_source_goldberg_radzik, TestBellmanFordAndGoldbergRadzik.test_find_negative_cycle_longer_cycle, TestBellmanFordAndGoldbergRadzik.test_find_negative_cycle_no_cycle, TestBellmanFordAndGoldbergRadzik.test_find_negative_cycle_single_edge; module: test_weighted
**unweighted.py** — function: _bidirectional_pred_succ, _single_shortest_path, _single_shortest_path_length, all_pairs_shortest_path, all_pairs_shortest_path_length, bidirectional_shortest_path; 2 imports; module: unweighted
**weighted.py** — function: _bellman_ford, _dijkstra, _dijkstra_multisource, _inner_bellman_ford, _weight_function, all_pairs_bellman_ford_path; 7 imports; module: weighted
**similarity.py** — function: _prepare_panther_paths, _simrank_similarity_numpy, _simrank_similarity_python, generate_random_paths, graph_edit_distance, optimal_edit_paths; 8 imports; module: similarity; rationale: [NOTE] fast reduce of Cv relies on it, [NOTE] index_map is modified in-place by `generate_random_paths`, [NOTE] inf remembered from Ce construction, [NOTE] the below performed anywhere from 4-10x faster, [TODO] support DiGraph
**simple_paths.py** — class: PathBuffer; function: _all_simple_edge_paths, _bidirectional_dijkstra, _bidirectional_pred_succ, _bidirectional_shortest_path, all_simple_edge_paths, all_simple_paths; 7 imports; method: PathBuffer.__init__, PathBuffer.__len__, PathBuffer.pop, PathBuffer.push; module: simple_paths
**smallworld.py** — function: lattice_reference, omega, random_reference, sigma; 6 imports; module: smallworld
**smetric.py** — function: s_metric; 1 imports; module: smetric
**sparsifiers.py** — function: _add_edge_to_spanner, _lightest_edge_dicts, _setup_residual_graph, spanner; 4 imports; module: sparsifiers
**structuralholes.py** — function: constraint, effective_size, local_constraint, mutual_weight, normalized_mutual_weight; 3 imports; module: structuralholes
**summarization.py** — function: _snap_build_graph, _snap_eligible_group, _snap_split, dedensify, snap_aggregation; 3 imports; module: summarization
**swap.py** — function: connected_double_edge_swap, directed_edge_swap, double_edge_swap; 3 imports; module: swap
**test_asteroidal.py** — function: test_is_at_free; 1 imports; module: test_asteroidal
**test_boundary.py** — class: TestEdgeBoundary, TestNodeBoundary; 5 imports; method: TestEdgeBoundary.test_complete_graph, TestEdgeBoundary.test_directed, TestEdgeBoundary.test_multidigraph, TestEdgeBoundary.test_multigraph, TestEdgeBoundary.test_null_graph, TestEdgeBoundary.test_path_graph; module: test_boundary
**test_bridges.py** — class: TestBridges, TestHasBridges, TestLocalBridges; 2 imports; method: TestBridges.test_barbell_graph, TestBridges.test_multiedge_bridge, TestBridges.test_single_bridge, TestHasBridges.test_bridges_multiple_components, TestHasBridges.test_has_bridges_raises_root_not_in_G, TestHasBridges.test_multiedge_bridge; module: test_bridges
**test_broadcasting.py** — function: test_binomial_tree_broadcast, test_empty_graph_broadcast, test_example_tree_broadcast, test_path_broadcast, test_raises_graph_type, test_raises_node_not_in_G; 3 imports; module: test_broadcasting
**test_chains.py** — class: TestChainDecomposition; function: cycles, cyclic_equals; 4 imports; method: TestChainDecomposition.assertContainsChain, TestChainDecomposition.test_barbell_graph, TestChainDecomposition.test_chain_decomposition_root_not_in_G, TestChainDecomposition.test_decomposition, TestChainDecomposition.test_disconnected_graph, TestChainDecomposition.test_disconnected_graph_root_node; module: test_chains
**test_chordal.py** — class: TestMCS; 2 imports; method: TestMCS.setup_class, TestMCS.test_chordal_find_cliques, TestMCS.test_chordal_find_cliquesCC, TestMCS.test_chordal_find_cliques_path, TestMCS.test_complete_to_chordal_graph, TestMCS.test_graph_treewidth; module: test_chordal
**test_clique.py** — class: TestCliques, TestEnumerateAllCliques; 3 imports; method: TestCliques.setup_method, TestCliques.test_directed, TestCliques.test_find_cliques1, TestCliques.test_find_cliques2, TestCliques.test_find_cliques3, TestCliques.test_find_cliques_directed; module: test_clique
**test_cluster.py** — class: TestAverageClustering, TestClustering, TestDirectedAverageClustering, TestDirectedClustering, TestDirectedWeightedClustering, TestGeneralizedDegree; function: test_all_triangles_complete_graph_exact, test_all_triangles_directed_graph, test_all_triangles_multiedges, test_all_triangles_no_triangles, test_all_triangles_non_integer_nodes, test_all_triangles_overlapping; 2 imports; method: TestAverageClustering.setup_class, TestAverageClustering.test_average_clustering, TestAverageClustering.test_average_clustering_signed, TestAverageClustering.test_empty, TestClustering.setup_class, TestClustering.test_clustering; module: test_cluster
**test_communicability.py** — class: TestCommunicability; 5 imports; method: TestCommunicability.test_communicability, TestCommunicability.test_communicability2; module: test_communicability
**test_core.py** — class: TestCore; 3 imports; method: TestCore.setup_class, TestCore.test_core_number, TestCore.test_core_number2, TestCore.test_core_number_multigraph, TestCore.test_core_number_self_loop, TestCore.test_directed_core_number; module: test_core
**test_covering.py** — class: TestIsEdgeCover, TestMinEdgeCover; 2 imports; method: TestIsEdgeCover.test_empty_graph, TestIsEdgeCover.test_graph_single_edge, TestIsEdgeCover.test_graph_with_loop, TestMinEdgeCover.test_bipartite_explicit, TestMinEdgeCover.test_complete_graph_even, TestMinEdgeCover.test_complete_graph_odd; module: test_covering
**test_cuts.py** — class: TestBoundaryExpansion, TestConductance, TestCutSize, TestEdgeExpansion, TestMixingExpansion, TestNodeExpansion; 1 imports; method: TestBoundaryExpansion.test_graph, TestConductance.test_graph, TestCutSize.test_directed, TestCutSize.test_directed_symmetric, TestCutSize.test_multigraph, TestCutSize.test_single_edge; module: test_cuts
**test_cycles.py** — class: TestCycleEnumeration, TestCycles, TestFindCycle, TestGirth, TestMinimumCycleBasis; function: assert_basis_equal, check_independent, cycle_edges, directed_cycle_edgeset, multigraph_cycle_edgeset, pairwise; 9 imports; method: TestCycleEnumeration.D, TestCycleEnumeration.K, TestCycleEnumeration.check_cycle, TestCycleEnumeration.check_cycle_algorithm, TestCycleEnumeration.check_cycle_enumeration_integer_sequence, TestCycleEnumeration.edgeset_function; module: test_cycles; rationale: [NOTE] we shuffle the labels of g to rule out accidentally-correct
**test_d_separation.py** — function: asia_graph, asia_graph_fixture, chain_and_fork_graph, collider_graph, collider_graph_fixture, collider_trek_graph; 3 imports; module: test_d_separation
**test_dag.py** — class: TestDAG, TestDagLongestPath, TestDagLongestPathLength, TestDagToBranching; function: _consume, test_ancestors_descendants_undirected, test_colliders, test_colliders_raise, test_is_aperiodic_bipartite, test_is_aperiodic_cycle; 7 imports; method: TestDAG._check_antichains, TestDAG.setup_class, TestDAG.test_all_topological_sorts_1, TestDAG.test_all_topological_sorts_2, TestDAG.test_all_topological_sorts_3, TestDAG.test_all_topological_sorts_4; module: test_dag
**test_distance_measures.py** — class: TestBarycenter, TestDistance, TestEffectiveGraphResistance, TestKemenyConstant, TestResistanceDistance, TestWeightedDistance; function: test__extrema_bounding_invalid_compute_kwarg; 7 imports; method: TestBarycenter.barycenter_as_subgraph, TestBarycenter.test_must_be_connected, TestBarycenter.test_sp_kwarg, TestBarycenter.test_this_one_specific_tree, TestBarycenter.test_trees, TestDistance.setup_method; module: test_distance_measures
**test_distance_regular.py** — class: TestDistanceRegular, TestStronglyRegular; function: test_empty_graph_raises, test_raises_on_directed_and_multigraphs; 3 imports; method: TestDistanceRegular.test_global_parameters, TestDistanceRegular.test_intersection_array, TestDistanceRegular.test_is_distance_regular, TestDistanceRegular.test_not_connected, TestStronglyRegular.test_cycle_graph, TestStronglyRegular.test_path_graph; module: test_distance_regular
**test_dominance.py** — class: TestDominanceFrontiers, TestImmediateDominators; 2 imports; method: TestDominanceFrontiers.test_boost_example, TestDominanceFrontiers.test_discard_issue, TestDominanceFrontiers.test_domrel_png, TestDominanceFrontiers.test_irreducible1, TestDominanceFrontiers.test_irreducible2, TestDominanceFrontiers.test_loop; module: test_dominance
**test_dominating.py** — function: test_complete, test_complete_graph_connected_dominating_set, test_connected_watts_strogatz_graph_connected_dominating_set, test_docstring_example_connected_dominating_set, test_dominating_set, test_is_connected_dominating_set; 2 imports; module: test_dominating
**test_efficiency.py** — class: TestEfficiency; 1 imports; method: TestEfficiency.setup_method, TestEfficiency.test_efficiency, TestEfficiency.test_efficiency_disconnected_nodes, TestEfficiency.test_global_efficiency, TestEfficiency.test_global_efficiency_complete_graph, TestEfficiency.test_local_efficiency_complete_graph; module: test_efficiency
**test_euler.py** — class: TestEulerianCircuit, TestEulerianPath, TestEulerize, TestFindPathStart, TestHasEulerianPath, TestIsEulerian; function: test_empty_graph_raises; 3 imports; method: TestEulerianCircuit.test_eulerian_circuit_cycle, TestEulerianCircuit.test_eulerian_circuit_digraph, TestEulerianCircuit.test_multigraph, TestEulerianCircuit.test_multigraph_with_keys, TestEulerianCircuit.test_not_eulerian, TestEulerianPath.test_eulerian_path; module: test_euler
**test_graph_hashing.py** — function: hexdigest_sizes_correct, is_subiteration, test_digest_size, test_digest_size_subgraph_hash, test_directed, test_directed_bugs; 3 imports; module: test_graph_hashing
**test_graphical.py** — class: TestAtlas; function: test_directed_degree_sequence, test_multi_sequence, test_negative_input, test_non_integer_input, test_numpy_degree_sequence, test_pseudo_sequence; 3 imports; method: TestAtlas.setup_class, TestAtlas.test_atlas; module: test_graphical
**test_hierarchy.py** — function: test_hierarchy_1, test_hierarchy_cycle, test_hierarchy_empty_graph, test_hierarchy_tree, test_hierarchy_undirected, test_hierarchy_weight; 2 imports; module: test_hierarchy
**test_hybrid.py** — function: test_2d_grid_graph, test_small_graph; 1 imports; module: test_hybrid
**test_isolate.py** — function: test_is_isolate, test_isolates, test_number_of_isolates; 1 imports; module: test_isolate
**test_link_prediction.py** — class: TestAdamicAdarIndex, TestCNSoundarajanHopcroft, TestCommonNeighborCentrality, TestJaccardCoefficient, TestPreferentialAttachment, TestRAIndexSoundarajanHopcroft; function: _test_func; 4 imports; method: TestAdamicAdarIndex.setup_class, TestAdamicAdarIndex.test_K5, TestAdamicAdarIndex.test_P3, TestAdamicAdarIndex.test_S4, TestAdamicAdarIndex.test_all_nonexistent_edges, TestAdamicAdarIndex.test_equal_nodes; module: test_link_prediction
**test_lowest_common_ancestors.py** — class: TestDAGLCA, TestMultiDiGraph_DAGLCA, TestMultiTreeLCA, TestTreeLCA; function: get_pair, test_all_pairs_lca_self_ancestors, test_lca_dont_rely_on_single_successor, test_lca_multiple_valid_solutions, test_lca_on_cycle_graph, test_lca_on_null_graph; 5 imports; method: TestDAGLCA.assert_lca_dicts_same, TestDAGLCA.setup_class, TestDAGLCA.test_all_pairs_lca_all_pairs_given, TestDAGLCA.test_all_pairs_lca_bug_gh4942, TestDAGLCA.test_all_pairs_lca_default_kwarg, TestDAGLCA.test_all_pairs_lca_generator; module: test_lowest_common_ancestors; rationale: [NOTE] order edge addition is critical to the test
**test_matching.py** — class: TestIsMatching, TestIsMaximalMatching, TestIsPerfectMatching, TestMaxWeightMatching, TestMaximalMatching; function: test_is_matching_invalid_edge, test_is_matching_node_not_in_G, test_wrong_graph_type; 5 imports; method: TestIsMatching.test_dict, TestIsMatching.test_edge_order, TestIsMatching.test_empty_matching, TestIsMatching.test_invalid_edge, TestIsMatching.test_invalid_matching, TestIsMatching.test_selfloops; module: test_matching
**test_max_weight_clique.py** — class: TestMaximumWeightClique; function: disconnected, empty_graph, one_node_graph, three_node_clique, three_node_independent_set, two_node_graph; 2 imports; method: TestMaximumWeightClique.test_30_node_prob, TestMaximumWeightClique.test_basic_cases, TestMaximumWeightClique.test_error_on_non_integer_weight, TestMaximumWeightClique.test_key_error, TestMaximumWeightClique.test_unaffected_by_self_loops; module: test_max_weight_clique
**test_mis.py** — function: test_K5, test_bipartite, test_exceptions, test_florentine_family, test_random_graphs, test_random_seed; 3 imports; module: test_mis
**test_moral.py** — function: test_get_moral_graph; 2 imports; module: test_moral
**test_node_classification.py** — class: TestHarmonicFunction, TestLocalAndGlobalConsistency; 3 imports; method: TestHarmonicFunction.test_digraph, TestHarmonicFunction.test_labeled_nodes_are_not_changed, TestHarmonicFunction.test_no_edges, TestHarmonicFunction.test_no_labels, TestHarmonicFunction.test_no_nodes, TestHarmonicFunction.test_nodes_all_labeled; module: test_node_classification
**test_non_randomness.py** — function: test_empty_graph, test_non_connected, test_non_randomness, test_not_implemented, test_self_loops, test_value_error; 2 imports; module: test_non_randomness
**test_perfect_graph.py** — function: test_chordal_graph, test_complement_of_odd_cycle, test_disconnected_union_of_cliques, test_even_cycle, test_odd_cycle; 1 imports; module: test_perfect_graph
**test_planar_drawing.py** — class: Vector; function: check_edge_intersections, check_embedding_data, check_triangulation, is_close, planar_drawing_conforms_to_embedding, point_in_between; 4 imports; method: Vector.__eq__, Vector.__ge__, Vector.__gt__, Vector.__init__, Vector.__le__, Vector.__lt__; module: test_planar_drawing
**test_planarity.py** — class: TestLRPlanarity, TestPlanarEmbeddingClass; function: check_counterexample, check_embedding; 5 imports; method: TestLRPlanarity.check_graph, TestLRPlanarity.test_comp, TestLRPlanarity.test_counterexample_planar, TestLRPlanarity.test_counterexample_planar_recursive, TestLRPlanarity.test_edge_removal_from_planar_embedding, TestLRPlanarity.test_goldner_harary; module: test_planarity
**test_polynomials.py** — function: test_chromatic_polynomial, test_chromatic_polynomial_disjoint, test_tutte_polynomial, test_tutte_polynomial_disjoint; 2 imports; module: test_polynomials
**test_reciprocity.py** — class: TestReciprocity; 2 imports; method: TestReciprocity.test_overall_reciprocity_empty_graph, TestReciprocity.test_reciprocity_digraph, TestReciprocity.test_reciprocity_graph_isolated_nodes, TestReciprocity.test_reciprocity_graph_node, TestReciprocity.test_reciprocity_graph_nodes; module: test_reciprocity
**test_regular.py** — class: TestIsKRegular, TestIsRegular, TestKFactor; 4 imports; method: TestIsKRegular.test_is_k_regular1, TestIsKRegular.test_is_k_regular2, TestIsKRegular.test_is_k_regular3, TestIsRegular.test_is_regular, TestIsRegular.test_is_regular_empty_graph_raises, TestKFactor.test_k_factor_complete; module: test_regular
**test_richclub.py** — function: test_rich_club_exception2, test_rich_club_leq_3_nodes_normalized, test_rich_club_leq_3_nodes_unnormalized, test_rich_club_selfloop, test_richclub, test_richclub2; 2 imports; module: test_richclub
**test_similarity.py** — class: TestSimilarity; function: ematch, getCanonical, nmatch, test_generate_random_paths_source_not_in_G, test_generate_random_paths_with_isolated_nodes; 9 imports; method: TestSimilarity.setup_class, TestSimilarity.testCopy, TestSimilarity.testGraph1, TestSimilarity.testGraph2, TestSimilarity.testGraph3, TestSimilarity.testGraph4; module: test_similarity; rationale: [NOTE] nx.simrank_similarity_numpy not included because returns np.array
**test_simple_paths.py** — class: TestIsSimplePath; function: hamiltonian_edge_path, hamiltonian_path, test_Greg_Bernstein, test_all_simple_edge_paths, test_all_simple_edge_paths_corner_cases, test_all_simple_edge_paths_cutoff; 9 imports; method: TestIsSimplePath.test_cycle, TestIsSimplePath.test_directed_cycle, TestIsSimplePath.test_directed_non_path, TestIsSimplePath.test_directed_path, TestIsSimplePath.test_empty_list, TestIsSimplePath.test_missing_node; module: test_simple_paths
**test_smallworld.py** — function: test_graph_no_edges, test_lattice_reference, test_omega, test_random_reference, test_sigma; 6 imports; module: test_smallworld
**test_smetric.py** — function: test_smetric; 2 imports; module: test_smetric
**test_sparsifiers.py** — function: _assign_random_weights, _test_spanner, test_spanner_invalid_stretch, test_spanner_trivial, test_spanner_unweighted_complete_graph, test_spanner_unweighted_disconnected_graph; 3 imports; module: test_sparsifiers
**test_structuralholes.py** — class: TestStructuralHoles, TestStructuralHolesNoScipy; function: test_constraint_isolated_node_with_selfloop, test_constraint_isolated_node_with_selfloop_using_nodes_kwarg, test_constraint_isolated_node_with_selfloop_weighted, test_constraint_isolated_node_with_selfloop_weighted_using_nodes_kwarg, test_effective_size_isolated_node_with_selfloop, test_effective_size_isolated_node_with_selfloop_weighted; 4 imports; method: TestStructuralHolesNoScipy.setup_method, TestStructuralHolesNoScipy.test_constraint_directed, TestStructuralHolesNoScipy.test_constraint_isolated, TestStructuralHolesNoScipy.test_constraint_undirected, TestStructuralHolesNoScipy.test_constraint_weighted_directed, TestStructuralHolesNoScipy.test_constraint_weighted_undirected; module: test_structuralholes
**test_summarization.py** — class: AbstractSNAP, TestDirectedDedensification, TestSNAPDirected, TestSNAPDirectedMulti, TestSNAPNoEdgeTypes, TestSNAPUndirected; function: test_summarization_empty; 2 imports; method: AbstractSNAP.build_original_graph, AbstractSNAP.build_summary_graph, AbstractSNAP.deterministic_labels, AbstractSNAP.test_summary_graph, TestDirectedDedensification.build_compressed_graph, TestDirectedDedensification.build_original_graph; module: test_summarization
**test_swap.py** — function: test_connected_double_edge_swap, test_connected_double_edge_swap_low_window_threshold, test_connected_double_edge_swap_not_connected, test_connected_double_edge_swap_small, test_connected_double_edge_swap_star, test_connected_double_edge_swap_star_low_window_threshold; 2 imports; module: test_swap; rationale: [TODO] Rewrite function to explicitly check for impossible swaps and raise error
**test_threshold.py** — class: TestGeneratorThreshold; function: test_threshold_graph_invalid_creation_sequence; 3 imports; method: TestGeneratorThreshold.test_create_using, TestGeneratorThreshold.test_creation_sequence_to_weights, TestGeneratorThreshold.test_creation_sequences, TestGeneratorThreshold.test_eigenvectors, TestGeneratorThreshold.test_fast_versions_properties_threshold_graphs, TestGeneratorThreshold.test_find_alternating_4_cycle; module: test_threshold
**test_time_dependent.py** — class: TestCdIndex; 4 imports; method: TestCdIndex.test_common_graph, TestCdIndex.test_common_graph_with_float_attributes, TestCdIndex.test_common_graph_with_given_attributes, TestCdIndex.test_common_graph_with_int_attributes, TestCdIndex.test_common_graph_with_weights, TestCdIndex.test_maximally_consolidating; module: test_time_dependent
**test_tournament.py** — function: test_bidirectional_edges, test_condition_not_satisfied, test_empty_iterable, test_graph_is_tournament, test_graph_is_tournament_one_node, test_graph_is_tournament_seed; 11 imports; module: test_tournament
**test_triads.py** — function: test_all_triads, test_is_triad, test_triad_type, test_triadic_census, test_triadic_census_correct_nodelist_values, test_triadic_census_four_path; 5 imports; module: test_triads
**test_vitality.py** — class: TestClosenessVitality; 1 imports; method: TestClosenessVitality.test_disconnecting_graph, TestClosenessVitality.test_unweighted, TestClosenessVitality.test_unweighted_digraph, TestClosenessVitality.test_weighted, TestClosenessVitality.test_weighted_digraph, TestClosenessVitality.test_weighted_multidigraph; module: test_vitality
**test_voronoi.py** — class: TestVoronoiCells; 2 imports; method: TestVoronoiCells.test_directed_inward, TestVoronoiCells.test_directed_unweighted, TestVoronoiCells.test_directed_weighted, TestVoronoiCells.test_isolates, TestVoronoiCells.test_multidigraph_unweighted, TestVoronoiCells.test_multidigraph_weighted; module: test_voronoi
**test_walks.py** — function: test_directed, test_hidden_weight_attr, test_negative_length_exception, test_non_integer_nodes, test_undirected, test_zero_length; 2 imports; module: test_walks
**test_wiener.py** — function: test_hyper_wiener_of_complete_graph, test_hyper_wiener_of_cycle_graph, test_hyper_wiener_of_disconnected_graph, test_hyper_wiener_of_path_graph, test_hyper_wiener_of_weighted_graph, test_schultz_and_gutman_index_of_complete_bipartite_graph_1; 1 imports; module: test_wiener
**threshold.py** — function: betweenness_sequence, cluster_sequence, creation_sequence, creation_sequence_to_weights, degree_correlation, degree_sequence; 3 imports; module: threshold
**time_dependent.py** — function: cd_index; 2 imports; module: time_dependent
**tournament.py** — function: hamiltonian_path, index_satisfying, is_reachable, is_strongly_connected, is_tournament, random_tournament; 5 imports; module: tournament
**__init__.py** — 5 imports; module: __init__
**beamsearch.py** — function: bfs_beam_edges; 1 imports; module: beamsearch
**breadth_first_search.py** — function: bfs_edges, bfs_labeled_edges, bfs_layers, bfs_predecessors, bfs_successors, bfs_tree; 2 imports; module: breadth_first_search
**depth_first_search.py** — function: dfs_edges, dfs_labeled_edges, dfs_postorder_nodes, dfs_predecessors, dfs_preorder_nodes, dfs_successors; 2 imports; module: depth_first_search
**edgebfs.py** — function: edge_bfs; 2 imports; module: edgebfs
**edgedfs.py** — function: edge_dfs; 1 imports; module: edgedfs
**test_beamsearch.py** — function: test_narrow, test_wide; 2 imports; module: test_beamsearch
**test_bfs.py** — class: TestBFS, TestBreadthLimitedSearch; 3 imports; method: TestBFS.setup_class, TestBFS.test_bfs_edges, TestBFS.test_bfs_edges_reverse, TestBFS.test_bfs_edges_sorting, TestBFS.test_bfs_labeled_edges_directed, TestBFS.test_bfs_layers; module: test_bfs
**test_dfs.py** — class: TestDFS, TestDepthLimitedSearch; 1 imports; method: TestDFS.setup_class, TestDFS.test_dfs_edges, TestDFS.test_dfs_edges_sorting, TestDFS.test_dfs_labeled_disconnected_edges, TestDFS.test_dfs_labeled_edges, TestDFS.test_dfs_labeled_edges_sorting; module: test_dfs; rationale: [NOTE] reverse-depth_limit edge types were not reported before gh-6240
**test_edgebfs.py** — class: TestEdgeBFS; 4 imports; method: TestEdgeBFS.setup_class, TestEdgeBFS.test_digraph, TestEdgeBFS.test_digraph2, TestEdgeBFS.test_digraph_ignore, TestEdgeBFS.test_digraph_ignore2, TestEdgeBFS.test_digraph_orientation_invalid; module: test_edgebfs
**test_edgedfs.py** — class: TestEdgeDFS; 5 imports; method: TestEdgeDFS.setup_class, TestEdgeDFS.test_digraph, TestEdgeDFS.test_digraph2, TestEdgeDFS.test_digraph_ignore, TestEdgeDFS.test_digraph_ignore2, TestEdgeDFS.test_digraph_orientation_invalid; module: test_edgedfs
**__init__.py** — 7 imports; module: __init__
**branchings.py** — class: ArborescenceIterator; function: _max_weight, _min_weight, branching_weight, greedy_branching, maximum_branching, maximum_spanning_arborescence; 9 imports; method: ArborescenceIterator.__init__, ArborescenceIterator.__iter__, ArborescenceIterator.__next__, ArborescenceIterator._clear_partition, ArborescenceIterator._partition, ArborescenceIterator._write_partition; module: branchings; rationale: [TODO] Implement method from Gabow, Galil, Spence and Tarjan:
**coding.py** — class: NotATree; function: from_nested_tuple, from_prufer_sequence, to_nested_tuple, to_prufer_sequence; 4 imports; module: coding
**decomposition.py** — function: junction_tree; 6 imports; module: decomposition
**distance_measures.py** — function: _subtree_sizes, center, centroid; 1 imports; module: distance_measures
**mst.py** — class: EdgePartition, SpanningTreeIterator; function: boruvka_mst_edges, kruskal_mst_edges, maximum_spanning_edges, maximum_spanning_tree, minimum_spanning_edges, minimum_spanning_tree; 14 imports; method: SpanningTreeIterator.__init__, SpanningTreeIterator.__iter__, SpanningTreeIterator.__next__, SpanningTreeIterator._clear_partition, SpanningTreeIterator._partition, SpanningTreeIterator._write_partition; module: mst
**operations.py** — function: join_trees; 4 imports; module: operations
**recognition.py** — function: is_arborescence, is_branching, is_forest, is_tree; 1 imports; module: recognition
**test_branchings.py** — function: G1, G2, assert_equal_branchings, build_branching, sorted_edges, test_arborescence_iterator_initial_partition; 6 imports; module: test_branchings
**test_coding.py** — class: TestNestedTuple, TestPruferSequence; 5 imports; method: TestNestedTuple.test_canonical_form, TestNestedTuple.test_decoding, TestNestedTuple.test_encoding, TestNestedTuple.test_nontree, TestNestedTuple.test_sensible_relabeling, TestNestedTuple.test_unknown_root; module: test_coding
**test_decomposition.py** — function: test_junction_tree_directed_cascade, test_junction_tree_directed_confounders, test_junction_tree_directed_unconnected_edges, test_junction_tree_directed_unconnected_nodes, test_junction_tree_undirected; 2 imports; module: test_decomposition
**test_distance_measures.py** — class: TestCenter, TestDistance; 3 imports; method: TestCenter.test_center_balanced_tree, TestCenter.test_center_directed, TestCenter.test_center_non_tree, TestCenter.test_center_path_graph, TestCenter.test_center_simple_tree, TestCenter.test_center_star_graph; module: test_distance_measures
**test_mst.py** — class: MinimumSpanningTreeTestBase, MultigraphMSTTestBase, TestBoruvka, TestKruskal, TestNumberSpanningTrees, TestPrim; function: test_random_spanning_tree_additive_large, test_random_spanning_tree_additive_small, test_random_spanning_tree_empty_graph, test_random_spanning_tree_multiplicative_large, test_random_spanning_tree_multiplicative_small, test_random_spanning_tree_single_node_graph; 7 imports; method: MinimumSpanningTreeTestBase.setup_method, MinimumSpanningTreeTestBase.test_attributes, MinimumSpanningTreeTestBase.test_disconnected, MinimumSpanningTreeTestBase.test_empty_graph, MinimumSpanningTreeTestBase.test_isolated_node, MinimumSpanningTreeTestBase.test_maximum_edges; module: test_mst
**test_operations.py** — function: _check_custom_label_attribute, test_basic, test_empty_sequence, test_first_label, test_single; 4 imports; module: test_operations
**test_recognition.py** — class: TestDirectedTreeRecognition, TestTreeRecognition; function: test_dag_nontree, test_disconnected_graph, test_emptybranch, test_is_arborescense_empty_graph_raises, test_is_branching_empty_graph_raises, test_multicycle; 2 imports; method: TestTreeRecognition.setup_class, TestTreeRecognition.test_is_forest, TestTreeRecognition.test_is_not_forest, TestTreeRecognition.test_is_not_tree, TestTreeRecognition.test_is_tree, TestTreeRecognition.test_null_forest; module: test_recognition
**triads.py** — function: _tricode, all_triads, is_triad, triad_type, triadic_census, triads_by_type; 6 imports; module: triads
**vitality.py** — function: closeness_vitality; 2 imports; module: vitality
**voronoi.py** — function: voronoi_cells; 2 imports; module: voronoi
**walks.py** — function: number_of_walks; 2 imports; module: walks
**wiener.py** — function: gutman_index, hyper_wiener_index, schultz_index, wiener_index; 2 imports; module: wiener
**__init__.py** — 11 imports; module: __init__
**coreviews.py** — class: AdjacencyView, AtlasView, FilterAdjacency, FilterAtlas, FilterMultiAdjacency, FilterMultiInner; 1 imports; method: AdjacencyView.__getitem__, AdjacencyView.copy, AtlasView.__getitem__, AtlasView.__getstate__, AtlasView.__init__, AtlasView.__iter__; module: coreviews
**digraph.py** — class: DiGraph, _CachedPropertyResetterAdjAndSucc, _CachedPropertyResetterPred; 12 imports; method: DiGraph.__init__, DiGraph.__new__, DiGraph.add_edge, DiGraph.add_edges_from, DiGraph.add_node, DiGraph.add_nodes_from; module: digraph; rationale: [NOTE] self._succ = self._adj  # successor
**filters.py** — class: show_nodes; function: hide_diedges, hide_edges, hide_multidiedges, hide_multiedges, hide_nodes, no_filter; method: show_nodes.__call__, show_nodes.__init__; module: filters
**function.py** — function: _create_describe_info_dict, add_cycle, add_path, add_star, all_neighbors, common_neighbors; 5 imports; module: function
**graph.py** — class: Graph, _CachedPropertyResetterAdj, _CachedPropertyResetterNode; 9 imports; method: Graph.__contains__, Graph.__getitem__, Graph.__init__, Graph.__iter__, Graph.__len__, Graph.__new__; module: graph
**graphviews.py** — function: generic_graph_view, reverse_view, subgraph_view; 9 imports; module: graphviews
**multidigraph.py** — class: MultiDiGraph; 13 imports; method: MultiDiGraph.__init__, MultiDiGraph.__new__, MultiDiGraph.add_edge, MultiDiGraph.adj, MultiDiGraph.degree, MultiDiGraph.edges; module: multidigraph
**multigraph.py** — class: MultiGraph; 9 imports; method: MultiGraph.__init__, MultiGraph.__new__, MultiGraph.add_edge, MultiGraph.add_edges_from, MultiGraph.adj, MultiGraph.copy; module: multigraph
**reportviews.py** — class: DegreeView, DiDegreeView, DiMultiDegreeView, EdgeDataView, EdgeView, EdgeViewABC; 4 imports; method: DegreeView.__getitem__, DegreeView.__iter__, DiDegreeView.__call__, DiDegreeView.__getitem__, DiDegreeView.__init__, DiDegreeView.__iter__; module: reportviews
**dispatch_interface.py** — class: LoopbackBackendInterface, LoopbackDiGraph, LoopbackGraph, LoopbackMultiDiGraph, LoopbackMultiGraph, LoopbackPlanarEmbedding; function: convert; 7 imports; method: LoopbackBackendInterface.__getattr__, LoopbackBackendInterface.can_run, LoopbackBackendInterface.convert_from_nx, LoopbackBackendInterface.convert_to_nx, LoopbackBackendInterface.graph__new__, LoopbackBackendInterface.on_start_tests; module: dispatch_interface
**historical_tests.py** — class: HistoricalTests; 5 imports; method: HistoricalTests.setup_class, HistoricalTests.test_add_edge, HistoricalTests.test_add_edges_from, HistoricalTests.test_add_edges_from2, HistoricalTests.test_add_edges_from3, HistoricalTests.test_add_nodes_from; module: historical_tests
**test_coreviews.py** — class: TestAdjacencyView, TestAtlasView, TestFilteredGraphs, TestMultiAdjacencyView, TestUnionAdjacency, TestUnionAtlas; 3 imports; method: TestAdjacencyView.setup_method, TestAdjacencyView.test_copy, TestAdjacencyView.test_getitem, TestAdjacencyView.test_items, TestAdjacencyView.test_iter, TestAdjacencyView.test_len; module: test_coreviews
**test_digraph.py** — class: BaseAttrDiGraphTester, BaseDiGraphTester, TestDiGraph, TestEdgeSubgraph; 7 imports; method: BaseAttrDiGraphTester.test_edges_data, BaseAttrDiGraphTester.test_in_degree_weighted, BaseAttrDiGraphTester.test_out_degree_weighted, BaseDiGraphTester.test_degree, BaseDiGraphTester.test_di_attributes_cached, BaseDiGraphTester.test_di_cache_reset; module: test_digraph
**test_digraph_historical.py** — class: TestDiGraphHistorical; 3 imports; method: TestDiGraphHistorical.setup_class, TestDiGraphHistorical.test_degree_digraph, TestDiGraphHistorical.test_in_degree, TestDiGraphHistorical.test_neighbors, TestDiGraphHistorical.test_out_degree, TestDiGraphHistorical.test_predecessors; module: test_digraph_historical
**test_filters.py** — class: TestFilterFactory; 2 imports; method: TestFilterFactory.test_hide_diedges, TestFilterFactory.test_hide_edges, TestFilterFactory.test_hide_multidiedges, TestFilterFactory.test_hide_multiedges, TestFilterFactory.test_hide_nodes, TestFilterFactory.test_no_filter; module: test_filters
**test_function.py** — class: TestCommonNeighbors, TestFunction; function: test_degree_histogram_empty, test_get_edge_attributes, test_get_node_attributes, test_is_empty, test_ispath, test_pathweight; 5 imports; method: TestCommonNeighbors.setup_class, TestCommonNeighbors.test_K5, TestCommonNeighbors.test_P3, TestCommonNeighbors.test_S4, TestCommonNeighbors.test_custom1, TestCommonNeighbors.test_custom2; module: test_function
**test_graph.py** — class: BaseAttrGraphTester, BaseGraphTester, TestEdgeSubgraph, TestGraph; function: test_degree_node_not_found_exception_message, test_graph_new_extra_args; 9 imports; method: BaseAttrGraphTester.add_attributes, BaseAttrGraphTester.deep_copy_attrdict, BaseAttrGraphTester.deepcopy_edge_attr, BaseAttrGraphTester.deepcopy_graph_attr, BaseAttrGraphTester.deepcopy_node_attr, BaseAttrGraphTester.different_attrdict; module: test_graph; rationale: [NOTE] even if this safeguard is deemed unnecessary to pass NetworkX tests,
**test_graph_historical.py** — class: TestGraphHistorical; 2 imports; method: TestGraphHistorical.setup_class; module: test_graph_historical
**test_graphviews.py** — class: TestChainsOfViews, TestMultiReverseView, TestReverseView, TestToDirected, TestToUndirected; function: test_generic_multitype; 5 imports; method: TestChainsOfViews.setup_class, TestChainsOfViews.test_copy_disubgraph, TestChainsOfViews.test_copy_multidisubgraph, TestChainsOfViews.test_copy_multisubgraph, TestChainsOfViews.test_copy_of_view, TestChainsOfViews.test_copy_subgraph; module: test_graphviews; rationale: [NOTE] SubGraph views are not tested here. They have their own testing file
**test_multidigraph.py** — class: BaseMultiDiGraphTester, CustomDictClass, MultiDiGraphSubClass, TestEdgeSubgraph, TestMultiDiGraph, TestMultiDiGraphSubclass; 7 imports; method: BaseMultiDiGraphTester.is_deep, BaseMultiDiGraphTester.is_shallow, BaseMultiDiGraphTester.test_degree, BaseMultiDiGraphTester.test_di_attributes_cached, BaseMultiDiGraphTester.test_edges, BaseMultiDiGraphTester.test_edges_data; module: test_multidigraph
**test_multigraph.py** — class: BaseMultiGraphTester, CustomDictClass, MultiGraphSubClass, TestEdgeSubgraph, TestMultiGraph, TestMultiGraphSubclass; 6 imports; method: BaseMultiGraphTester.deepcopy_edge_attr, BaseMultiGraphTester.different_attrdict, BaseMultiGraphTester.graphs_equal, BaseMultiGraphTester.same_attrdict, BaseMultiGraphTester.shallow_copy_edge_attr, BaseMultiGraphTester.test_adjacency; module: test_multigraph
**test_reportviews.py** — class: TestDegreeView, TestDiDegreeView, TestDiMultiDegreeView, TestEdgeDataView, TestEdgeView, TestInDegreeView; function: test_cache_dict_get_set_state, test_edge_views_inherit_from_EdgeViewABC, test_nodedataview_unhashable, test_slicing_reportviews; 6 imports; method: TestDegreeView.setup_class, TestDegreeView.test_getitem, TestDegreeView.test_iter, TestDegreeView.test_len, TestDegreeView.test_nbunch, TestDegreeView.test_pickle; module: test_reportviews
**test_special.py** — class: TestSpecialDiGraph, TestSpecialGraph, TestSpecialMultiDiGraph, TestSpecialMultiGraph, TestThinDiGraph, TestThinGraph; function: test_factories; 7 imports; method: TestSpecialDiGraph.setup_method, TestSpecialGraph.setup_method, TestSpecialMultiDiGraph.setup_method, TestSpecialMultiGraph.setup_method, TestThinDiGraph.setup_method, TestThinGraph.setup_method; module: test_special
**test_subgraphviews.py** — class: TestEdgeSubGraph, TestInducedSubGraph, TestMultiDiGraphView, TestMultiGraphView, TestSubDiGraphView, TestSubGraphView; 3 imports; method: TestEdgeSubGraph.setup_class, TestEdgeSubGraph.test_add_node, TestEdgeSubGraph.test_correct_edges, TestEdgeSubGraph.test_correct_nodes, TestEdgeSubGraph.test_edge_attr_dict, TestEdgeSubGraph.test_graph_attr_dict; module: test_subgraphviews
**conftest.py** — function: add_nx, pytest_addoption, pytest_collection_modifyitems, pytest_configure, set_warnings; 12 imports; module: conftest; rationale: [TODO] The warnings below need to be dealt with, but for now we silence them.
**convert.py** — function: from_dict_of_dicts, from_dict_of_lists, from_edgelist, to_dict_of_dicts, to_dict_of_lists, to_edgelist; 7 imports; module: convert; rationale: [NOTE] most general check - should remain last in order of execution
**convert_matrix.py** — function: _coo_gen_triples, _csc_gen_triples, _csr_gen_triples, _dok_gen_triples, _generate_weighted_edges, from_numpy_array; 6 imports; module: convert_matrix
**__init__.py** — 5 imports; module: __init__
**layout.py** — function: _energy_fruchterman_reingold, _fruchterman_reingold, _kamada_kawai_costfn, _kamada_kawai_solve, _process_params, _sparse_fruchterman_reingold; 5 imports; module: layout; rationale: [TODO] revisit w/ sparse 1D container
**nx_agraph.py** — function: from_agraph, graphviz_layout, pygraphviz_layout, read_dot, to_agraph, view_pygraphviz; 4 imports; module: nx_agraph
**nx_latex.py** — function: to_latex, to_latex_raw, write_latex; 1 imports; module: nx_latex
**nx_pydot.py** — function: from_pydot, graphviz_layout, pydot_layout, read_dot, to_pydot, write_dot; 4 imports; module: nx_pydot; rationale: [NOTE] Pydot v3 expects a dummy argument whereas Pydot v4 doesn't
**nx_pylab.py** — class: CurvedArrowTextBase, FancyArrowFactory; function: apply_alpha, apply_matplotlib_colors, display, draw, draw_bipartite, draw_circular; 19 imports; method: CurvedArrowTextBase.__init__, CurvedArrowTextBase._get_arrow_path_disp, CurvedArrowTextBase._update_text_pos_angle, CurvedArrowTextBase.draw, FancyArrowFactory.__call__, FancyArrowFactory.__init__; module: nx_pylab; rationale: [NOTE] Arrowstyle modification must occur after the warnings section
**test_agraph.py** — class: TestAGraph; 6 imports; method: TestAGraph.assert_equal, TestAGraph.build_graph, TestAGraph.test_2d_layout, TestAGraph.test_3d_layout, TestAGraph.test_agraph_roundtripping, TestAGraph.test_from_agraph_create_using; module: test_agraph; rationale: [NOTE] test depends on layout prog being deterministic
**test_image_comparison_pylab_mpl.py** — function: test_display_complex, test_display_empty_graph, test_display_house_with_colors, test_display_labels_and_colors, test_display_shortest_path, test_house_with_colors; 3 imports; module: test_image_comparison_pylab_mpl
**test_latex.py** — function: test_basic_multiple_graphs, test_basic_tikz, test_exception_multigraph, test_exception_multiple_graphs, test_exception_pos_single_graph, test_tikz_attributes; 2 imports; module: test_latex
**test_layout.py** — class: TestLayout; function: _num_nodes_per_bfs_layer, test_bfs_layout_barbell, test_bfs_layout_complete_graph, test_bfs_layout_disconnected, test_bipartite_layout_default_nodes, test_bipartite_layout_default_nodes_raises_non_bipartite_input; 3 imports; method: TestLayout.check_kamada_kawai_costfn, TestLayout.check_scale_and_center, TestLayout.setup_class, TestLayout.test_adjacency_interface_numpy, TestLayout.test_adjacency_interface_scipy, TestLayout.test_arf_layout_negative_a_check; module: test_layout
**test_pydot.py** — class: TestPydot; function: test_hashable_pydot, test_pydot_issue_7581, test_pydot_numerical_name; 4 imports; method: TestPydot.test_pydot, TestPydot.test_read_write; module: test_pydot
**test_pylab.py** — function: subplots, test_alpha_iter, test_apply_alpha, test_arrows, test_axes, test_directed_edges_linestyle_default; 10 imports; module: test_pylab; rationale: [NOTE] When node_shape is a sequence, draw_networkx_nodes internally calls, [NOTE] parametrizing on marker to test both branches of internal, [NOTE] parametrizing on marker to test both branches of internal, [NOTE] parametrizing on marker to test both branches of internal
**exception.py** — class: AmbiguousSolution, ExceededMaxIterations, HasACycle, NetworkXAlgorithmError, NetworkXError, NetworkXException; method: PowerIterationFailedConvergence.__init__; module: exception
**__init__.py** — 29 imports; module: __init__
**atlas.py** — function: _generate_graphs, graph_atlas, graph_atlas_g; 4 imports; module: atlas
**classic.py** — function: _tree_edges, balanced_tree, barbell_graph, binomial_tree, circulant_graph, circular_ladder_graph; 7 imports; module: classic
**cographs.py** — function: random_cograph; 2 imports; module: cographs
**community.py** — function: LFR_benchmark_graph, _generate_communities, _generate_min_degree, _hurwitz_zeta, _powerlaw_sequence, _zipf_rv_below; 5 imports; module: community
**degree_seq.py** — class: DegreeSequenceRandomGraph; function: _configuration_model, _to_stublist, configuration_model, degree_sequence_tree, directed_configuration_model, directed_havel_hakimi_graph; 9 imports; method: DegreeSequenceRandomGraph.__init__, DegreeSequenceRandomGraph.generate, DegreeSequenceRandomGraph.p, DegreeSequenceRandomGraph.phase1, DegreeSequenceRandomGraph.phase2, DegreeSequenceRandomGraph.phase3; module: degree_seq
**directed.py** — function: _random_k_out_graph_numpy, _random_k_out_graph_python, gn_graph, gnc_graph, gnr_graph, random_k_out_graph; 9 imports; module: directed
**duplication.py** — function: duplication_divergence_graph, partial_duplication_graph; 4 imports; module: duplication
**ego.py** — function: ego_graph; 1 imports; module: ego
**expanders.py** — function: chordal_cycle_graph, is_regular_expander, margulis_gabber_galil_graph, maybe_regular_expander, maybe_regular_expander_graph, paley_graph; 5 imports; module: expanders
**geometric.py** — function: _geometric_edges, geographical_threshold_graph, geometric_edges, geometric_soft_configuration_graph, navigable_small_world_graph, random_geometric_graph; 8 imports; module: geometric; rationale: [NOTE] See _geometric_edges for the actual implementation. The reason this
**harary_graph.py** — function: hkn_harary_graph, hnm_harary_graph; 2 imports; module: harary_graph
**internet_as_graphs.py** — class: AS_graph_generator; function: choose_pref_attach, random_internet_as_graph, uniform_int_from_avg; 3 imports; method: AS_graph_generator.__init__, AS_graph_generator.add_cp_peering_link, AS_graph_generator.add_customer, AS_graph_generator.add_edge, AS_graph_generator.add_m_peering_link, AS_graph_generator.add_node; module: internet_as_graphs
**intersection.py** — function: general_random_intersection_graph, k_random_intersection_graph, uniform_random_intersection_graph; 3 imports; module: intersection
**interval_graph.py** — function: interval_graph; 2 imports; module: interval_graph
**joint_degree_seq.py** — function: _directed_neighbor_switch, _directed_neighbor_switch_rev, _neighbor_switch, directed_joint_degree_graph, is_valid_directed_joint_degree, is_valid_joint_degree; 2 imports; module: joint_degree_seq
**lattice.py** — function: grid_2d_graph, grid_graph, hexagonal_lattice_graph, hypercube_graph, triangular_lattice_graph; 14 imports; module: lattice
**line.py** — function: _find_partition, _lg_directed, _lg_undirected, _odd_triangle, _select_starting_cell, _triangles; 6 imports; module: line
**mycielski.py** — function: mycielski_graph, mycielskian; 2 imports; module: mycielski
**nonisomorphic_trees.py** — function: _layout_to_graph, _layout_to_matrix, _next_rooted_tree, _next_tree, _rooted_trees, _split_tree; 2 imports; module: nonisomorphic_trees
**random_clustered.py** — function: random_clustered_graph; 2 imports; module: random_clustered
**random_graphs.py** — function: _random_subset, barabasi_albert_graph, connected_watts_strogatz_graph, dense_gnm_random_graph, dual_barabasi_albert_graph, extended_barabasi_albert_graph; 13 imports; module: random_graphs
**small.py** — function: LCF_graph, _raise_on_directed, bull_graph, chvatal_graph, cubical_graph, desargues_graph; 7 imports; module: small
**social.py** — function: davis_southern_women_graph, florentine_families_graph, karate_club_graph, les_miserables_graph; 1 imports; module: social
**spectral_graph_forge.py** — function: spectral_graph_forge; 4 imports; module: spectral_graph_forge
**stochastic.py** — function: stochastic_graph; 4 imports; module: stochastic
**sudoku.py** — function: sudoku_graph; 2 imports; module: sudoku
**test_atlas.py** — class: TestAtlasGraph, TestAtlasGraphG; 9 imports; method: TestAtlasGraph.test_graph, TestAtlasGraph.test_index_too_large, TestAtlasGraph.test_index_too_small, TestAtlasGraphG.setup_class, TestAtlasGraphG.test_names, TestAtlasGraphG.test_nondecreasing_degree_sequence; module: test_atlas
**test_classic.py** — class: TestGeneratorClassic; 6 imports; method: TestGeneratorClassic.test_balanced_tree, TestGeneratorClassic.test_balanced_tree_path, TestGeneratorClassic.test_balanced_tree_star, TestGeneratorClassic.test_barbell_graph, TestGeneratorClassic.test_binomial_tree, TestGeneratorClassic.test_circulant_graph; module: test_classic
**test_cographs.py** — function: test_random_cograph; 2 imports; module: test_cographs
**test_community.py** — function: test_both_degrees_none, test_caveman_graph, test_connected_caveman_graph, test_gaussian_random_partition_graph, test_generate_min_degree_itr, test_generator; 2 imports; module: test_community
**test_degree_seq.py** — class: TestConfigurationModel; function: test_degree_sequence_tree, test_degree_sequence_tree_directed, test_degree_sequence_tree_invalid_degree_sequence, test_directed_configuration_model, test_directed_configuration_raise_unequal, test_directed_havel_hakimi; 2 imports; method: TestConfigurationModel.test_degree_sequence, TestConfigurationModel.test_degree_zero, TestConfigurationModel.test_directed_disallowed, TestConfigurationModel.test_empty_degree_sequence, TestConfigurationModel.test_odd_degree_sum, TestConfigurationModel.test_random_seed; module: test_degree_seq
**test_directed.py** — class: TestGeneratorsDirected, TestRandomKOutGraph, TestUniformRandomKOutGraph; function: test_non_numeric_ordering, test_scale_free_graph_initial_graph_kwarg, test_scale_free_graph_negative_delta; 13 imports; method: TestGeneratorsDirected.test_create_using_keyword_arguments, TestGeneratorsDirected.test_parameters, TestGeneratorsDirected.test_smoke_test_random_graphs, TestRandomKOutGraph.f, TestRandomKOutGraph.nkalpha, TestRandomKOutGraph.test_negative_alpha; module: test_directed
**test_duplication.py** — class: TestDuplicationDivergenceGraph, TestPartialDuplicationGraph; 2 imports; method: TestDuplicationDivergenceGraph.test_create_using, TestDuplicationDivergenceGraph.test_final_size, TestDuplicationDivergenceGraph.test_minimum_desired_nodes, TestDuplicationDivergenceGraph.test_non_extreme_probability_value, TestDuplicationDivergenceGraph.test_probability_too_large, TestDuplicationDivergenceGraph.test_probability_too_small; module: test_duplication
**test_ego.py** — class: TestGeneratorEgo; 3 imports; method: TestGeneratorEgo.test_ego, TestGeneratorEgo.test_ego_distance; module: test_ego
**test_expanders.py** — function: test_chordal_cycle_graph, test_chordal_cycle_graph_badinput, test_is_regular_expander, test_is_regular_expander_badinput, test_margulis_gabber_galil_graph_badinput, test_margulis_gabber_galil_graph_eigvals; 2 imports; module: test_expanders
**test_geometric.py** — class: TestGeographicalThresholdGraph, TestNavigableSmallWorldGraph, TestRandomGeometricGraph, TestSoftRandomGeometricGraph, TestThresholdedRandomGeometricGraph, TestWaxmanGraph; function: join, l1dist, test_beta_clustering_S1, test_compare_mean_kappas_different_gammas_S1, test_dict_kappas_S1, test_geometric_edges_pos_attribute; 6 imports; method: TestGeographicalThresholdGraph.test_distances, TestGeographicalThresholdGraph.test_metric, TestGeographicalThresholdGraph.test_number_of_nodes, TestGeographicalThresholdGraph.test_p_dist_zero, TestGeographicalThresholdGraph.test_pos_weight_name, TestNavigableSmallWorldGraph.test_invalid_diameter_value; module: test_geometric
**test_harary_graph.py** — class: TestHararyGraph; 5 imports; method: TestHararyGraph.test_hkn_harary_graph, TestHararyGraph.test_hnm_harary_graph; module: test_harary_graph
**test_internet_as_graphs.py** — class: TestInternetASTopology; function: test_AS_graph_coverage, test_choose_pref_attach; 7 imports; method: TestInternetASTopology.set_customers, TestInternetASTopology.set_providers, TestInternetASTopology.setup_class, TestInternetASTopology.test_connectivity, TestInternetASTopology.test_degree_values, TestInternetASTopology.test_node_numbers; module: test_internet_as_graphs
**test_intersection.py** — class: TestIntersectionGraph; 2 imports; method: TestIntersectionGraph.test_general_random_intersection_graph, TestIntersectionGraph.test_k_random_intersection_graph, TestIntersectionGraph.test_k_random_intersection_graph_seeded, TestIntersectionGraph.test_random_intersection_graph; module: test_intersection
**test_interval_graph.py** — class: TestIntervalGraph; 5 imports; method: TestIntervalGraph.test_empty, TestIntervalGraph.test_interval_graph_0, TestIntervalGraph.test_interval_graph_1, TestIntervalGraph.test_interval_graph_2, TestIntervalGraph.test_interval_graph_3, TestIntervalGraph.test_interval_graph_4; module: test_interval_graph
**test_joint_degree_seq.py** — function: test_directed_joint_degree_graph, test_is_valid_directed_joint_degree, test_is_valid_joint_degree, test_joint_degree_graph; 8 imports; module: test_joint_degree_seq
**test_lattice.py** — class: TestGrid2DGraph, TestGridGraph, TestHexagonalLatticeGraph, TestHypercubeGraph, TestTriangularLatticeGraph; function: test_2D_lattice_no_contraction_leftovers, test_hexagonal_lattice_no_pos; 4 imports; method: TestGrid2DGraph.test_degree_distribution, TestGrid2DGraph.test_directed, TestGrid2DGraph.test_exceptions, TestGrid2DGraph.test_multigraph, TestGrid2DGraph.test_node_input, TestGrid2DGraph.test_number_of_vertices; module: test_lattice
**test_line.py** — class: TestGeneratorInverseLine, TestGeneratorLine, TestGeneratorPrivateFunctions; 4 imports; method: TestGeneratorInverseLine.test_K1, TestGeneratorInverseLine.test_cycle, TestGeneratorInverseLine.test_edgeless_graph, TestGeneratorInverseLine.test_empty, TestGeneratorInverseLine.test_example, TestGeneratorInverseLine.test_example_2; module: test_line
**test_mycielski.py** — class: TestMycielski; 2 imports; method: TestMycielski.test_construction, TestMycielski.test_mycielski_graph_generator, TestMycielski.test_size; module: test_mycielski
**test_nonisomorphic_trees.py** — class: TestGeneratorNonIsomorphicTrees; function: test_nonisomorphic_tree_low_order_agreement, test_nonisomorphic_tree_negative_order, test_nonisomorphic_tree_order_0, test_nonisomorphic_tree_order_1; 3 imports; method: TestGeneratorNonIsomorphicTrees.test_nonisomorphic_trees, TestGeneratorNonIsomorphicTrees.test_nonisomorphism, TestGeneratorNonIsomorphicTrees.test_number_of_nonisomorphic_trees, TestGeneratorNonIsomorphicTrees.test_tree_structure; module: test_nonisomorphic_trees
**test_random_clustered.py** — class: TestRandomClusteredGraph; 2 imports; method: TestRandomClusteredGraph.test_custom_joint_degree_sequence, TestRandomClusteredGraph.test_directed_graph_raises_error, TestRandomClusteredGraph.test_invalid_joint_degree_sequence_type, TestRandomClusteredGraph.test_invalid_joint_degree_sequence_value, TestRandomClusteredGraph.test_tuple_joint_degree_sequence; module: test_random_clustered
**test_random_graphs.py** — class: TestGeneratorsRandom; function: test_barabasi_albert_disallow_directed_and_multigraph, test_connected_watts_strogatz, test_connected_watts_strogatz_graph_disconnected, test_connected_watts_strogatz_zero_tries, test_create_using, test_dual_barabasi_albert_disallow_directed_and_multigraph; 2 imports; method: TestGeneratorsRandom.test_dual_barabasi_albert, TestGeneratorsRandom.test_extended_barabasi_albert, TestGeneratorsRandom.test_gnm, TestGeneratorsRandom.test_random_graph, TestGeneratorsRandom.test_random_kernel_graph, TestGeneratorsRandom.test_random_kernel_graph_default_root; module: test_random_graphs
**test_small.py** — class: TestGeneratorsSmall; function: tests_raises_with_directed_create_using; 2 imports; method: TestGeneratorsSmall.test__LCF_graph, TestGeneratorsSmall.test_properties_of_named_small_graphs; module: test_small
**test_spectral_graph_forge.py** — function: test_spectral_graph_forge; 6 imports; module: test_spectral_graph_forge
**test_stochastic.py** — class: TestStochasticGraph; 2 imports; method: TestStochasticGraph.test_arbitrary_weights, TestStochasticGraph.test_default_weights, TestStochasticGraph.test_graph_disallowed, TestStochasticGraph.test_in_place, TestStochasticGraph.test_multidigraph, TestStochasticGraph.test_multigraph_disallowed; module: test_stochastic
**test_sudoku.py** — function: test_sudoku_generator, test_sudoku_negative; 2 imports; module: test_sudoku
**test_time_series.py** — function: test_visibility_graph__concave_series__path_graph, test_visibility_graph__convex_series__complete_graph, test_visibility_graph__empty_series__empty_graph, test_visibility_graph__flat_series__path_graph, test_visibility_graph__single_value_ts__single_node_graph, test_visibility_graph__two_values_ts__single_edge_graph; 2 imports; module: test_time_series
**test_trees.py** — function: test_basic_prefix_tree, test_implementations_consistent, test_random_labeled_rooted_forest, test_random_labeled_rooted_forest_n_zero, test_random_labeled_rooted_tree, test_random_labeled_tree_n_zero; 5 imports; module: test_trees
**test_triads.py** — function: test_invalid_name, test_triad_graph; 2 imports; module: test_triads
**time_series.py** — function: visibility_graph; 2 imports; module: time_series
**trees.py** — function: _bicenter, _num_rooted_forests, _num_rooted_trees, _num_trees, _random_unlabeled_rooted_forest, _random_unlabeled_rooted_tree; 6 imports; module: trees
**triads.py** — function: triad_graph; 2 imports; module: triads
**lazy_imports.py** — class: DelayedImportErrorModule; function: _lazy_import, attach; 6 imports; method: DelayedImportErrorModule.__getattr__, DelayedImportErrorModule.__init__; module: lazy_imports
**__init__.py** — 13 imports; module: __init__
**algebraicconnectivity.py** — class: _LUSolver, _PCGSolver; function: _get_fiedler_func, _preprocess_graph, _rcm_estimate, _tracemin_fiedler, algebraic_connectivity, fiedler_vector; 6 imports; method: _LUSolver.__init__, _LUSolver.solve, _PCGSolver.__init__, _PCGSolver._solve, _PCGSolver.solve; module: algebraicconnectivity
**attrmatrix.py** — function: _edge_value, _node_value, attr_matrix, attr_sparse_matrix; 3 imports; module: attrmatrix
**bethehessianmatrix.py** — function: bethe_hessian_matrix; 3 imports; module: bethehessianmatrix
**graphmatrix.py** — function: adjacency_matrix, incidence_matrix; 2 imports; module: graphmatrix
**laplacianmatrix.py** — function: _transition_matrix, directed_combinatorial_laplacian_matrix, directed_laplacian_matrix, laplacian_matrix, normalized_laplacian_matrix; 4 imports; module: laplacianmatrix; rationale: [NOTE] P has type ndarray if walk_type=="pagerank", else csr_array, [NOTE] This could be sparsified for the non-pagerank cases, [NOTE] could be improved by not densifying
**modularitymatrix.py** — function: directed_modularity_matrix, modularity_matrix; 3 imports; module: modularitymatrix
**spectrum.py** — function: adjacency_spectrum, bethe_hessian_spectrum, laplacian_spectrum, modularity_spectrum, normalized_laplacian_spectrum; 2 imports; module: spectrum
**test_algebraic_connectivity.py** — class: TestAlgebraicConnectivity, TestSpectralOrdering; function: check_eigenvector, test_algebraic_connectivity_tracemin_chol, test_fiedler_vector_tracemin_chol, test_fiedler_vector_tracemin_unknown, test_spectral_bisection, test_spectral_ordering_tracemin_chol; 3 imports; method: TestAlgebraicConnectivity.test_abbreviation_of_method, TestAlgebraicConnectivity.test_buckminsterfullerene, TestAlgebraicConnectivity.test_cycle, TestAlgebraicConnectivity.test_directed, TestAlgebraicConnectivity.test_disconnected, TestAlgebraicConnectivity.test_null_and_singleton; module: test_algebraic_connectivity
**test_attrmatrix.py** — function: test_attr_matrix, test_attr_matrix_directed, test_attr_matrix_multigraph, test_attr_sparse_matrix, test_attr_sparse_matrix_directed; 2 imports; module: test_attrmatrix
**test_bethehessian.py** — class: TestBetheHessian; 2 imports; method: TestBetheHessian.setup_class, TestBetheHessian.test_bethe_hessian; module: test_bethehessian
**test_graphmatrix.py** — class: TestGraphMatrix; function: test_incidence_matrix_simple; 3 imports; method: TestGraphMatrix.setup_class, TestGraphMatrix.test_adjacency_matrix, TestGraphMatrix.test_incidence_matrix, TestGraphMatrix.test_weighted_incidence_matrix; module: test_graphmatrix
**test_laplacian.py** — class: TestLaplacian; function: test_directed_combinatorial_laplacian, test_directed_laplacian; 2 imports; method: TestLaplacian.setup_class, TestLaplacian.test_laplacian, TestLaplacian.test_normalized_laplacian; module: test_laplacian
**test_modularity.py** — class: TestModularity; 2 imports; method: TestModularity.setup_class, TestModularity.test_directed_modularity, TestModularity.test_modularity, TestModularity.test_modularity_weight; module: test_modularity
**test_spectrum.py** — class: TestSpectrum; 2 imports; method: TestSpectrum.setup_class, TestSpectrum.test_adjacency_spectrum, TestSpectrum.test_bethe_hessian_spectrum, TestSpectrum.test_laplacian_spectrum, TestSpectrum.test_modularity_spectrum, TestSpectrum.test_normalized_laplacian_spectrum; module: test_spectrum
**__init__.py** — 12 imports; module: __init__
**adjlist.py** — function: generate_adjlist, parse_adjlist, read_adjlist, write_adjlist; 4 imports; module: adjlist
**edgelist.py** — function: generate_edgelist, parse_edgelist, read_edgelist, read_weighted_edgelist, write_edgelist, write_weighted_edgelist; 3 imports; module: edgelist
**gexf.py** — class: GEXF, GEXFReader, GEXFWriter; function: generate_gexf, read_gexf, relabel_gexf_graph, write_gexf; 10 imports; method: GEXF.construct_types, GEXF.set_version, GEXFReader.__call__, GEXFReader.__init__, GEXFReader.add_edge, GEXFReader.add_node; module: gexf
**gml.py** — class: Pattern, Token; function: escape, generate_gml, literal_destringizer, literal_stringizer, parse_gml, parse_gml_lines; 11 imports; module: gml
**graph6.py** — function: _generate_graph6_bytes, data_to_n, from_graph6_bytes, n_to_data, read_graph6, to_graph6_bytes; 5 imports; module: graph6
**graphml.py** — class: GraphML, GraphMLReader, GraphMLWriter, GraphMLWriterLxml, IncrementalElement; function: generate_graphml, parse_graphml, read_graphml, write_graphml_lxml, write_graphml_xml; 10 imports; method: GraphML.construct_types, GraphML.get_xml_type, GraphMLReader.__call__, GraphMLReader.__init__, GraphMLReader.add_edge, GraphMLReader.add_node; module: graphml
**__init__.py** — 4 imports; module: __init__
**adjacency.py** — function: adjacency_data, adjacency_graph; 1 imports; module: adjacency
**cytoscape.py** — function: cytoscape_data, cytoscape_graph; 1 imports; module: cytoscape
**node_link.py** — function: _to_tuple, node_link_data, node_link_graph; 3 imports; module: node_link
**test_adjacency.py** — class: TestAdjacency; 7 imports; method: TestAdjacency.test_adjacency_form_json_serialisable, TestAdjacency.test_digraph, TestAdjacency.test_exception, TestAdjacency.test_graph, TestAdjacency.test_graph_attributes, TestAdjacency.test_input_data_is_not_modified_when_building_graph; module: test_adjacency
**test_cytoscape.py** — function: test_digraph, test_exception, test_graph, test_graph_attributes, test_input_data_is_not_modified_when_building_graph, test_multidigraph; 6 imports; module: test_cytoscape
**test_node_link.py** — class: TestNodeLink; 5 imports; method: TestNodeLink.test_custom_attrs, TestNodeLink.test_digraph, TestNodeLink.test_exception, TestNodeLink.test_exception_dep, TestNodeLink.test_graph, TestNodeLink.test_graph_attributes; module: test_node_link
**test_tree.py** — function: test_exceptions, test_graph, test_graph_attributes; 5 imports; module: test_tree
**tree.py** — function: tree_data, tree_graph; 2 imports; module: tree
**leda.py** — function: parse_leda, read_leda; 3 imports; module: leda
**multiline_adjlist.py** — function: generate_multiline_adjlist, parse_multiline_adjlist, read_multiline_adjlist, write_multiline_adjlist; 5 imports; module: multiline_adjlist
**p2g.py** — function: parse_p2g, read_p2g, write_p2g; 2 imports; module: p2g
**pajek.py** — function: generate_pajek, make_qstr, parse_pajek, read_pajek, write_pajek; 4 imports; module: pajek
**sparse6.py** — function: _generate_sparse6_bytes, from_sparse6_bytes, read_sparse6, to_sparse6_bytes, write_sparse6; 6 imports; module: sparse6
**test_adjlist.py** — class: TestAdjlist, TestGenerateAdjlist, TestMultilineAdjlist; function: test_adjlist_rstrip_parsing; 6 imports; method: TestAdjlist.setup_class, TestAdjlist.test_adjlist_delimiter, TestAdjlist.test_adjlist_digraph, TestAdjlist.test_adjlist_graph, TestAdjlist.test_adjlist_integers, TestAdjlist.test_adjlist_multidigraph; module: test_adjlist
**test_edgelist.py** — class: TestEdgelist; function: example_graph, test_comments_None, test_edgelist_consistent_strip_handling, test_parse_edgelist, test_parse_edgelist_no_data, test_parse_edgelist_with_data_dict; 7 imports; method: TestEdgelist.setup_class, TestEdgelist.test_edgelist_digraph, TestEdgelist.test_edgelist_graph, TestEdgelist.test_edgelist_integers, TestEdgelist.test_edgelist_multidigraph, TestEdgelist.test_edgelist_multigraph; module: test_edgelist
**test_gexf.py** — class: TestGEXF; function: test_dynamic_graph_has_timeformat, test_gexf_v1_3; 5 imports; method: TestGEXF.setup_class, TestGEXF.test_add_parent, TestGEXF.test_bool, TestGEXF.test_default_attribute, TestGEXF.test_directed_edge_in_undirected, TestGEXF.test_dynamic_mode; module: test_gexf
**test_gml.py** — class: TestGraph, TestPropertyLists; function: byte_file, test_stringize_empty_list_tuple; 11 imports; method: TestGraph.setup_class, TestGraph.test_data_types, TestGraph.test_escape_unescape, TestGraph.test_exceptions, TestGraph.test_float_label, TestGraph.test_graph_types; module: test_gml
**test_graph6.py** — class: TestFromGraph6Bytes, TestGraph6Utils, TestReadGraph6, TestToGraph6Bytes, TestWriteGraph6; function: test_from_graph6_invariant_to_trailing_newline, test_from_graph6_raises_header_newline; 6 imports; method: TestFromGraph6Bytes.test_from_graph6_bytes, TestFromGraph6Bytes.test_read_equals_from_bytes, TestGraph6Utils.test_n_data_n_conversion, TestReadGraph6.test_read_many_graph6, TestToGraph6Bytes.test_complete_bipartite_graph, TestToGraph6Bytes.test_complete_graph; module: test_graph6
**test_graphml.py** — class: BaseGraphML, TestReadGraphML, TestWriteGraphML, TestXMLGraphML; function: test_empty_attribute, test_exception_for_unsupported_datatype_edge_attr, test_exception_for_unsupported_datatype_graph_attr, test_exception_for_unsupported_datatype_node_attr; 9 imports; method: BaseGraphML.setup_class, TestReadGraphML.test_bool, TestReadGraphML.test_directed_edge_in_undirected, TestReadGraphML.test_graphml_header_line, TestReadGraphML.test_hyperedge_raise, TestReadGraphML.test_key_raise; module: test_graphml
**test_leda.py** — class: TestLEDA; 2 imports; method: TestLEDA.test_parse_leda, TestLEDA.test_read_LEDA; module: test_leda
**test_p2g.py** — class: TestP2G; 5 imports; method: TestP2G.setup_class, TestP2G.test_read_p2g, TestP2G.test_write_p2g, TestP2G.test_write_read_p2g; module: test_p2g
**test_pajek.py** — class: TestPajek; 5 imports; method: TestPajek.setup_class, TestPajek.test_ignored_attribute, TestPajek.test_noname, TestPajek.test_parse_pajek, TestPajek.test_parse_pajek_mat, TestPajek.test_parse_pajek_simple; module: test_pajek
**test_sparse6.py** — class: TestSparseGraph6, TestWriteSparse6; 5 imports; method: TestSparseGraph6.test_from_bytes_multigraph_graph, TestSparseGraph6.test_from_sparse6_bytes, TestSparseGraph6.test_read_many_graph6, TestSparseGraph6.test_read_sparse6, TestWriteSparse6.test_complete_bipartite, TestWriteSparse6.test_complete_graph; module: test_sparse6
**test_text.py** — function: generate_test_graphs, test_collapse_directed, test_collapse_undirected, test_generate_network_text_directed_multi_tree, test_generate_network_text_forest_directed, test_generate_network_text_forest_undirected; 6 imports; module: test_text
**text.py** — class: AsciiBaseGlyphs, AsciiDirectedGlyphs, AsciiUndirectedGlyphs, BaseGlyphs, UtfBaseGlyphs, UtfDirectedGlyphs; function: _find_sources, _parse_network_text, generate_network_text, write_network_text; 7 imports; method: BaseGlyphs.as_dict; module: text; rationale: [NOTE] it may be skipped later, but we don't have that, [NOTE] the order of mapping differs between pypy and cpython
**relabel.py** — function: _relabel_copy, _relabel_inplace, convert_node_labels_to_integers, relabel_nodes; 1 imports; module: relabel
**test_all_random_functions.py** — function: run_all_random_functions, t, test_rng_interface; 5 imports; module: test_all_random_functions
**test_convert.py** — class: TestConvert; function: test_to_dict_of_dicts_with_edgedata_and_nodelist, test_to_dict_of_dicts_with_edgedata_multigraph, test_to_dict_of_dicts_with_edgedata_param, test_to_networkx_graph_non_edgelist; 12 imports; method: TestConvert.edgelists_equal, TestConvert.test_attribute_dict_integrity, TestConvert.test_custom_node_attr_dict_safekeeping, TestConvert.test_digraphs, TestConvert.test_directed_to_undirected, TestConvert.test_edgelists; module: test_convert
**test_convert_numpy.py** — class: TestConvertNumpyArray; function: multigraph_test_graph, test_from_numpy_array_nodelist, test_from_numpy_array_nodelist_bad_size, test_from_numpy_array_nodelist_directed, test_from_numpy_array_nodelist_multigraph, test_from_numpy_array_nodelist_rountrip; 4 imports; method: TestConvertNumpyArray.assert_equal, TestConvertNumpyArray.create_weighted, TestConvertNumpyArray.identity_conversion, TestConvertNumpyArray.setup_method, TestConvertNumpyArray.test_dtype_int_graph, TestConvertNumpyArray.test_dtype_int_multigraph; module: test_convert_numpy
**test_convert_pandas.py** — class: TestConvertPandas; function: test_from_pandas_adjacency_with_index_collisions, test_to_pandas_adjacency_with_nodelist, test_to_pandas_edgelist_with_nodelist; 5 imports; method: TestConvertPandas.setup_method, TestConvertPandas.test_edgekey_with_multigraph, TestConvertPandas.test_edgekey_with_normal_graph_no_action, TestConvertPandas.test_exceptions, TestConvertPandas.test_from_adjacency, TestConvertPandas.test_from_adjacency_named; module: test_convert_pandas; rationale: [NOTE] this also tests that edge_attr can be `source`
**test_convert_scipy.py** — class: TestConvertScipy; function: test_from_scipy_sparse_array_formats; 3 imports; method: TestConvertScipy.create_weighted, TestConvertScipy.identity_conversion, TestConvertScipy.setup_method, TestConvertScipy.test_empty, TestConvertScipy.test_exceptions, TestConvertScipy.test_format_keyword; module: test_convert_scipy
**test_exceptions.py** — function: test_raises_networkx_no_path, test_raises_networkx_pointless_concept, test_raises_networkx_unbounded, test_raises_networkx_unfeasible, test_raises_networkxalgorithmerr, test_raises_networkxerr; 2 imports; module: test_exceptions
**test_import.py** — function: test_namespace_alias, test_namespace_nesting; 3 imports; module: test_import
**test_lazy_imports.py** — function: test_lazy_attach, test_lazy_import_basics, test_lazy_import_impact_on_sys_modules, test_lazy_import_nonbuiltins; 4 imports; module: test_lazy_imports
**test_relabel.py** — class: TestRelabel; 5 imports; method: TestRelabel.test_convert_node_labels_to_integers, TestRelabel.test_convert_to_integers2, TestRelabel.test_convert_to_integers_raise, TestRelabel.test_relabel_circular, TestRelabel.test_relabel_copy_name, TestRelabel.test_relabel_isolated_nodes_to_same; module: test_relabel
**test_removed_functions_exception_messages.py** — function: test_random_tree; 2 imports; module: test_removed_functions_exception_messages
**__init__.py** — 8 imports; module: __init__
**backends.py** — class: _LazyArgsRepr, _dispatchable; function: _always_run, _comma_sep_to_list, _do_nothing, _get_backends, _get_cache_key, _get_from_cache; 29 imports; method: _LazyArgsRepr.__init__, _LazyArgsRepr.__repr__, _dispatchable.__doc__, _dispatchable.__new__, _dispatchable.__reduce__, _dispatchable.__signature__; module: backends; rationale: [NOTE] "networkx" is in `backend_info` but ignored in `backends` and `config.backends`.
**configs.py** — class: BackendPriorities, Config, NetworkXConfig; function: _flexible_repr; 5 imports; method: BackendPriorities._on_delattr, BackendPriorities._on_setattr, Config.__call__, Config.__contains__, Config.__delattr__, Config.__delitem__; module: configs
**decorators.py** — class: argmap; function: nodes_or_number, not_implemented_for, np_random_state, open_file, py_random_state; 12 imports; method: argmap.__call__, argmap.__init__, argmap._count, argmap._flatten, argmap._indent, argmap._lazy_compile; module: decorators
**heaps.py** — class: BinaryHeap, MinHeap, PairingHeap; 4 imports; method: BinaryHeap.__init__, BinaryHeap.get, BinaryHeap.insert, BinaryHeap.min, BinaryHeap.pop, MinHeap.__bool__; module: heaps
**mapped_queue.py** — class: MappedQueue, _HeapElement; 1 imports; method: MappedQueue.__init__, MappedQueue.__len__, MappedQueue._heapify, MappedQueue._siftdown, MappedQueue._siftup, MappedQueue.pop; module: mapped_queue
**misc.py** — class: PythonRandomInterface, PythonRandomViaNumpyBits; function: _clear_cache, _dict_to_numpy_array1, _dict_to_numpy_array2, arbitrary_element, check_create_using, create_py_random_state; 12 imports; method: PythonRandomInterface.__init__, PythonRandomInterface.choice, PythonRandomInterface.expovariate, PythonRandomInterface.gauss, PythonRandomInterface.paretovariate, PythonRandomInterface.randint; module: misc; rationale: [NOTE] the numpy implementations of `choice` don't support strings, so
**random_sequence.py** — function: cumulative_distribution, discrete_sequence, is_valid_tree_degree_sequence, powerlaw_sequence, random_weighted_sample, weighted_choice; 3 imports; module: random_sequence
**rcm.py** — function: connected_cuthill_mckee_ordering, cuthill_mckee_ordering, pseudo_peripheral_node, reverse_cuthill_mckee_ordering; 4 imports; module: rcm
**test__init.py** — function: test_utils_namespace; 5 imports; module: test__init
**test_backends.py** — function: _stub_func, test_bad_backend_name, test_dispatch_graph_new, test_dispatch_kwds_vs_args, test_dispatchable_are_functions, test_graph_converter_needs_backend; 6 imports; module: test_backends
**test_config.py** — class: EmptyConfig, ExampleConfig; function: test_config_defaults, test_config_empty, test_config_subclass, test_context, test_not_strict, test_nxconfig; 6 imports; method: ExampleConfig._on_setattr; module: test_config
**test_decorators.py** — class: TestArgmap, TestOpenFileDecorator, TestRandomState; function: test_not_implemented_decorator, test_not_implemented_decorator_key, test_not_implemented_decorator_raise, test_py_random_state_invalid_arg_index, test_py_random_state_string_arg_index, test_random_state_invalid_arg_index; 13 imports; method: TestArgmap.test_actual_kwarg, TestArgmap.test_actual_vararg, TestArgmap.test_contextmanager, TestArgmap.test_flatten, TestArgmap.test_immediate_raise, TestArgmap.test_indent; module: test_decorators
**test_heaps.py** — class: X; function: _test_heap_class, test_BinaryHeap, test_PairingHeap; 4 imports; method: X.__eq__, X.__ge__, X.__gt__, X.__hash__, X.__le__, X.__lt__; module: test_heaps
**test_mapped_queue.py** — class: TestMappedDict, TestMappedQueue; function: test_HeapElement_eq, test_HeapElement_getitem, test_HeapElement_gtlt, test_HeapElement_gtlt_tied_priority, test_HeapElement_iter; 3 imports; method: TestMappedDict._make_mapped_queue, TestMappedDict.test_empty_pop, TestMappedDict.test_incomparable_ties, TestMappedDict.test_init, TestMappedDict.test_pop, TestMappedDict.test_push; module: test_mapped_queue
**test_misc.py** — class: TestNumpyArray; function: test_PythonRandomInterface_Generator, test_PythonRandomInterface_RandomState, test_arbitrary_element, test_arbitrary_element_raises, test_create_py_random_state, test_create_random_state; 19 imports; method: TestNumpyArray.setup_class, TestNumpyArray.test__dict_to_numpy_array1, TestNumpyArray.test__dict_to_numpy_array2, TestNumpyArray.test_dict_to_numpy_array_a, TestNumpyArray.test_dict_to_numpy_array_b, TestNumpyArray.test_numpy_to_list_of_ints; module: test_misc
**test_random_sequence.py** — function: test_degree_sequences, test_random_sequence_low_precision, test_random_weighted_choice, test_random_weighted_sample, test_valid_degree_sequence, test_zipf_rv; 2 imports; module: test_random_sequence
**test_rcm.py** — function: test_rcm_alternate_heuristic, test_reverse_cuthill_mckee; 2 imports; module: test_rcm
**test_unionfind.py** — function: test_empty_union, test_subtree_union, test_unbalanced_merge_weights, test_unionfind, test_unionfind_weights; 1 imports; module: test_unionfind
**union_find.py** — class: UnionFind; 1 imports; method: UnionFind.__getitem__, UnionFind.__init__, UnionFind.__iter__, UnionFind.to_sets, UnionFind.union; module: union_find
**__init__.py** — function: main; 3 imports; module: __init__
**__main__.py** — 3 imports; module: __main__
**__pip-runner__.py** — class: PipImportRedirectingFinder; function: version_str; 4 imports; method: PipImportRedirectingFinder.find_spec; module: __pip-runner__
**__init__.py** — function: main; 4 imports; module: __init__
**build_env.py** — class: BuildEnvironment, NoOpBuildEnvironment, _Prefix; function: _dedup, _get_system_sitepackages, get_runnable_pip; 30 imports; method: BuildEnvironment.__enter__, BuildEnvironment.__exit__, BuildEnvironment.__init__, BuildEnvironment._install_requirements, BuildEnvironment.check_requirements, BuildEnvironment.install_requirements; module: build_env; rationale: [FIXME] Consider direct URL?
**cache.py** — class: Cache, CacheEntry, EphemWheelCache, SimpleWheelCache, WheelCache; function: _hash_dict; 20 imports; method: Cache.__init__, Cache._get_cache_path_parts, Cache._get_candidates, Cache.get, Cache.get_path_for_link, CacheEntry.__init__; module: cache; rationale: [TODO] use DirectUrl.equivalent when
**__init__.py** — module: __init__
**autocompletion.py** — function: auto_complete_paths, autocomplete, get_path_completion_type; 12 imports; module: autocompletion
**base_command.py** — class: Command; 38 imports; method: Command.__init__, Command._main, Command.add_options, Command.handle_pip_version_check, Command.main, Command.parse_args; module: base_command; rationale: [TODO] Try to get these passing down from the command?
**cmdoptions.py** — class: PipOption; function: _convert_python_version, _get_format_control, _handle_config_settings, _handle_merge_hash, _handle_no_binary, _handle_no_cache_dir; 26 imports; module: cmdoptions
**command_context.py** — class: CommandContextMixIn; 5 imports; method: CommandContextMixIn.__init__, CommandContextMixIn.enter_context, CommandContextMixIn.main_context; module: command_context
**main.py** — function: main; 12 imports; module: main
**main_parser.py** — function: create_main_parser, identify_python_interpreter, parse_command; 15 imports; module: main_parser; rationale: [NOTE] parser calls disable_interspersed_args(), so the result of this
**parser.py** — class: ConfigOptionParser, CustomOptionParser, PrettyHelpFormatter, UpdatingDefaultsHelpFormatter; 16 imports; method: ConfigOptionParser.__init__, ConfigOptionParser._get_ordered_configuration_items, ConfigOptionParser._update_defaults, ConfigOptionParser.check_default, ConfigOptionParser.error, ConfigOptionParser.get_default_values; module: parser
**progress_bars.py** — function: _rich_progress_bar, get_download_progress_renderer; 18 imports; module: progress_bars
**req_command.py** — class: IndexGroupCommand, RequirementCommand, SessionCommandMixin; function: _create_truststore_ssl_context, warn_if_run_as_root, with_cleanup; 40 imports; method: IndexGroupCommand.handle_pip_version_check, RequirementCommand.__init__, RequirementCommand._build_package_finder, RequirementCommand.determine_resolver_variant, RequirementCommand.get_requirements, RequirementCommand.make_requirement_preparer; module: req_command; rationale: [NOTE] options.require_hashes may be set if --require-hashes is True
**spinners.py** — class: InteractiveSpinner, NonInteractiveSpinner, RateLimiter, SpinnerInterface; function: hidden_cursor, open_spinner; 10 imports; method: InteractiveSpinner.__init__, InteractiveSpinner._write, InteractiveSpinner.finish, InteractiveSpinner.spin, NonInteractiveSpinner.__init__, NonInteractiveSpinner._update; module: spinners
**status_codes.py** — module: status_codes
**__init__.py** — function: create_command, get_similar_commands; 7 imports; module: __init__
**cache.py** — class: CacheCommand; 12 imports; method: CacheCommand._cache_dir, CacheCommand._find_http_files, CacheCommand._find_wheels, CacheCommand.add_options, CacheCommand.format_for_abspath, CacheCommand.format_for_human; module: cache
**check.py** — class: CheckCommand; 10 imports; method: CheckCommand.run; module: check
**completion.py** — class: CompletionCommand; 7 imports; method: CompletionCommand.add_options, CompletionCommand.run; module: completion
**configuration.py** — class: ConfigurationCommand; 18 imports; method: ConfigurationCommand._determine_editor, ConfigurationCommand._determine_file, ConfigurationCommand._get_n_args, ConfigurationCommand._save_configuration, ConfigurationCommand.add_options, ConfigurationCommand.get_name; module: configuration
**debug.py** — class: DebugCommand; function: ca_bundle_info, create_vendor_txt_map, get_module_from_module_name, get_vendor_version_from_module, show_actual_vendor_versions, show_sys_implementation; 22 imports; method: DebugCommand.add_options, DebugCommand.run; module: debug
**download.py** — class: DownloadCommand; 15 imports; method: DownloadCommand.add_options, DownloadCommand.run; module: download
**freeze.py** — class: FreezeCommand; function: _dev_pkgs, _should_suppress_build_backends; 9 imports; method: FreezeCommand.add_options, FreezeCommand.run; module: freeze
**hash.py** — class: HashCommand; function: _hash_of_file; 12 imports; method: HashCommand.add_options, HashCommand.run; module: hash
**help.py** — class: HelpCommand; 8 imports; method: HelpCommand.run; module: help
**index.py** — class: IndexCommand; 23 imports; method: IndexCommand._build_package_finder, IndexCommand.add_options, IndexCommand.get_available_package_versions, IndexCommand.run; module: index
**inspect.py** — class: InspectCommand; 15 imports; method: InspectCommand._dist_to_dict, InspectCommand.add_options, InspectCommand.run; module: inspect
**install.py** — class: InstallCommand; function: create_os_error_message, decide_user_install, get_lib_location_guesses, site_packages_writable; 43 imports; method: InstallCommand._determine_conflicts, InstallCommand._handle_target_dir, InstallCommand._warn_about_conflicts, InstallCommand.add_options, InstallCommand.run; module: install; rationale: [NOTE] There is some duplication here, with commands/check.py
**list.py** — class: ListCommand; function: format_for_columns, format_for_json; 25 imports; method: ListCommand._build_package_finder, ListCommand.add_options, ListCommand.get_not_required, ListCommand.get_outdated, ListCommand.get_uptodate, ListCommand.iter_packages_latest_infos; module: list
**search.py** — class: SearchCommand; function: highest_version, print_dist_installation_info, print_results, transform_hits; 23 imports; method: SearchCommand.add_options, SearchCommand.run, SearchCommand.search; module: search
**show.py** — class: ShowCommand, _PackageInfo; function: print_results, search_packages_info; 15 imports; method: ShowCommand.add_options, ShowCommand.run; module: show
**uninstall.py** — class: UninstallCommand; 15 imports; method: UninstallCommand.add_options, UninstallCommand.run; module: uninstall
**wheel.py** — class: WheelCommand; 19 imports; method: WheelCommand.add_options, WheelCommand.run; module: wheel
**configuration.py** — class: Configuration; function: _disassemble_key, _normalize_name, get_configuration_files; 18 imports; method: Configuration.__init__, Configuration.__repr__, Configuration._construct_parser, Configuration._dictionary, Configuration._ensure_have_load_only, Configuration._get_parser_to_modify; module: configuration; rationale: [NOTE] Dictionaries are not populated if not loaded. So, conditionals, [NOTE] Maybe use the optionx attribute to normalize keynames., [XXX] This is patched in the tests., [XXX] This is patched in the tests.
**__init__.py** — function: make_distribution_for_install_requirement; 4 imports; module: __init__
**base.py** — class: AbstractDistribution; 5 imports; method: AbstractDistribution.__init__, AbstractDistribution.build_tracker_id, AbstractDistribution.get_metadata_distribution, AbstractDistribution.prepare_distribution_metadata; module: base
**installed.py** — class: InstalledDistribution; 4 imports; method: InstalledDistribution.build_tracker_id, InstalledDistribution.get_metadata_distribution, InstalledDistribution.prepare_distribution_metadata; module: installed
**sdist.py** — class: SourceDistribution; 11 imports; method: SourceDistribution._get_build_requires_editable, SourceDistribution._get_build_requires_wheel, SourceDistribution._install_build_reqs, SourceDistribution._prepare_build_backend, SourceDistribution._raise_conflicts, SourceDistribution._raise_missing_reqs; module: sdist
**wheel.py** — class: WheelDistribution; 7 imports; method: WheelDistribution.build_tracker_id, WheelDistribution.get_metadata_distribution, WheelDistribution.prepare_distribution_metadata; module: wheel
**exceptions.py** — class: BadCommand, BestVersionAlreadyInstalled, CommandError, ConfigurationError, ConfigurationFileCouldNotBeLoaded, DiagnosticPipError; function: _is_kebab_case, _prefix_with_indent; 29 imports; method: ConfigurationFileCouldNotBeLoaded.__init__, ConfigurationFileCouldNotBeLoaded.__str__, DiagnosticPipError.__init__, DiagnosticPipError.__repr__, DiagnosticPipError.__rich_console__, ExternallyManagedEnvironment.__init__; module: exceptions
**__init__.py** — module: __init__
**collector.py** — class: CacheablePageContent, CollectedSources, HTMLLinkParser, IndexContent, LinkCollector, ParseLinks; function: _ensure_api_header, _ensure_api_response, _get_encoding_from_headers, _get_index_content, _get_simple_response, _handle_get_simple_fail; 38 imports; method: CacheablePageContent.__eq__, CacheablePageContent.__hash__, CacheablePageContent.__init__, HTMLLinkParser.__init__, HTMLLinkParser.get_href, HTMLLinkParser.handle_starttag; module: collector; rationale: [TODO] In the future, it would be nice if pip supported PEP 691
**package_finder.py** — class: BestCandidateResult, CandidateEvaluator, CandidatePreferences, LinkEvaluator, LinkType, PackageFinder; function: _check_link_requires_python, _extract_version_from_fragment, _find_name_version_sep, filter_unallowed_hashes; 40 imports; method: BestCandidateResult.__init__, BestCandidateResult.iter_all, BestCandidateResult.iter_applicable, CandidateEvaluator.__init__, CandidateEvaluator._sort_key, CandidateEvaluator.compute_best_candidate; module: package_finder
**sources.py** — class: LinkSource, _FlatDirectorySource, _FlatDirectoryToUrls, _IndexDirectorySource, _LocalFileSource, _RemoteFileSource; function: _is_html_file, build_source; 21 imports; method: LinkSource.file_links, LinkSource.link, LinkSource.page_candidates, _FlatDirectorySource.__init__, _FlatDirectorySource.file_links, _FlatDirectorySource.link; module: sources
**__init__.py** — function: _fix_abiflags, _log_context, _looks_like_bpo_44860, _looks_like_deb_system_dist_packages, _looks_like_debian_scheme, _looks_like_msys2_mingw_scheme; 27 imports; module: __init__
**_distutils.py** — function: distutils_scheme, get_bin_prefix, get_platlib, get_purelib, get_scheme; 17 imports; module: _distutils; rationale: [NOTE] setting user or home has the side-effect of creating the home dir, [XXX] In old virtualenv versions, sys.prefix can contain '..' components,
**_sysconfig.py** — function: _infer_home, _infer_prefix, _infer_user, _should_use_osx_framework_prefix, get_bin_prefix, get_platlib; 13 imports; module: _sysconfig
**base.py** — function: change_root, get_major_minor_version, get_src_prefix, is_osx_framework; 9 imports; module: base; rationale: [FIXME] keep src in cwd for now (it is not a temporary folder)
**main.py** — function: main; 3 imports; module: main
**__init__.py** — class: Backend; function: _should_use_importlib_metadata, get_default_environment, get_directory_distribution, get_environment, get_metadata_distribution, get_wheel_distribution; 20 imports; module: __init__
**_json.py** — function: json_name, msg_to_json; 8 imports; module: _json
**base.py** — class: BaseDistribution, BaseEntryPoint, BaseEnvironment, FilesystemWheel, MemoryWheel, RequiresEntry; function: _convert_installed_files_path; 41 imports; method: BaseDistribution.__repr__, BaseDistribution.__str__, BaseDistribution._add_egg_info_requires, BaseDistribution._iter_declared_entries_from_legacy, BaseDistribution._iter_declared_entries_from_record, BaseDistribution._iter_egg_info_dependencies; module: base; rationale: [TODO] Move definition here., [TODO] get project location from second line of egg_link file, [TODO] this property is relatively costly to compute, memoize it ?
**__init__.py** — 2 imports; module: __init__
**_compat.py** — class: BadMetadata, BasePath; function: get_dist_name, get_info_location; 5 imports; method: BadMetadata.__init__, BadMetadata.__str__, BasePath.name, BasePath.parent; module: _compat
**_dists.py** — class: Distribution, WheelDistribution; 30 imports; method: Distribution.__init__, Distribution._get_dist_name_from_location, Distribution._metadata_impl, Distribution.canonical_name, Distribution.from_directory, Distribution.from_metadata_file_contents; module: _dists
**_envs.py** — class: Environment, _DistributionFinder; function: _emit_egg_deprecation, _looks_like_wheel; 29 imports; method: Environment.__init__, Environment._iter_distributions, Environment.default, Environment.from_paths, Environment.get_distribution, _DistributionFinder.__init__; module: _envs
**pkg_resources.py** — class: Distribution, EntryPoint, Environment, InMemoryMetadata; 31 imports; method: Distribution.__init__, Distribution._metadata_impl, Distribution.canonical_name, Distribution.from_directory, Distribution.from_metadata_file_contents, Distribution.from_wheel; module: pkg_resources
**__init__.py** — module: __init__
**candidate.py** — class: InstallationCandidate; 3 imports; method: InstallationCandidate.__init__, InstallationCandidate.__repr__, InstallationCandidate.__str__; module: candidate
**direct_url.py** — class: ArchiveInfo, DirInfo, DirectUrl, DirectUrlValidationError, VcsInfo; function: _exactly_one_of, _filter_none, _get, _get_required; 10 imports; method: ArchiveInfo.__init__, ArchiveInfo._from_dict, ArchiveInfo._to_dict, ArchiveInfo.hash, DirInfo.__init__, DirInfo._from_dict; module: direct_url
**format_control.py** — class: FormatControl; 5 imports; method: FormatControl.__eq__, FormatControl.__init__, FormatControl.__repr__, FormatControl.disallow_binaries, FormatControl.get_allowed_formats, FormatControl.handle_mutual_excludes; module: format_control
**index.py** — class: PackageIndex; 1 imports; method: PackageIndex.__init__, PackageIndex._url_for_path; module: index
**installation_report.py** — class: InstallationReport; 6 imports; method: InstallationReport.__init__, InstallationReport._install_req_to_dict, InstallationReport.to_dict; module: installation_report; rationale: [TODO] currently, the resolver uses the default environment to evaluate
**link.py** — class: Link, LinkHash, MetadataFile, _CleanResult; function: _clean_file_url_path, _clean_link, _clean_url_path, _clean_url_path_part, _ensure_quoted_url, links_equivalent; 29 imports; method: Link.__init__, Link.__repr__, Link.__str__, Link._egg_fragment, Link.as_hashes, Link.ext; module: link
**scheme.py** — class: Scheme; method: Scheme.__init__; module: scheme
**search_scope.py** — class: SearchScope; 11 imports; method: SearchScope.__init__, SearchScope.create, SearchScope.get_formatted_locations, SearchScope.get_index_urls_locations; module: search_scope
**selection_prefs.py** — class: SelectionPreferences; 2 imports; method: SelectionPreferences.__init__; module: selection_prefs
**target_python.py** — class: TargetPython; 9 imports; method: TargetPython.__init__, TargetPython.format_given, TargetPython.get_sorted_tags, TargetPython.get_unsorted_tags; module: target_python
**wheel.py** — class: Wheel; 6 imports; method: Wheel.__init__, Wheel.find_most_preferred_tag, Wheel.get_formatted_file_tags, Wheel.support_index_min, Wheel.supported; module: wheel
**__init__.py** — module: __init__
**auth.py** — class: Credentials, KeyRingBaseProvider, KeyRingCliProvider, KeyRingNullProvider, KeyRingPythonProvider, MultiDomainBasicAuth; function: get_keyring_provider; 31 imports; method: KeyRingBaseProvider.get_auth_info, KeyRingBaseProvider.save_auth_info, KeyRingCliProvider.__init__, KeyRingCliProvider._get_password, KeyRingCliProvider._set_password, KeyRingCliProvider.get_auth_info; module: auth
**cache.py** — class: SafeFileCache; function: is_from_cache, suppressed_cache_errors; 13 imports; method: SafeFileCache.__init__, SafeFileCache._get_cache_path, SafeFileCache._write, SafeFileCache.delete, SafeFileCache.get, SafeFileCache.get_body; module: cache
**download.py** — class: BatchDownloader, Downloader; function: _get_http_response_filename, _get_http_response_size, _http_get_download, _prepare_download, parse_content_disposition, sanitize_content_filename; 21 imports; method: BatchDownloader.__call__, BatchDownloader.__init__, Downloader.__call__, Downloader.__init__; module: download
**lazy_wheel.py** — class: HTTPRangeRequestUnsupported, LazyZipOverHTTP; function: dist_from_wheel_url; 22 imports; method: LazyZipOverHTTP.__enter__, LazyZipOverHTTP.__exit__, LazyZipOverHTTP.__init__, LazyZipOverHTTP._check_zip, LazyZipOverHTTP._download, LazyZipOverHTTP._merge; module: lazy_wheel; rationale: [TODO] Get range requests to be correctly cached
**session.py** — class: CacheControlAdapter, HTTPAdapter, InsecureCacheControlAdapter, InsecureHTTPAdapter, LocalFSAdapter, PipSession; function: looks_like_ci, user_agent; 48 imports; method: InsecureCacheControlAdapter.cert_verify, InsecureHTTPAdapter.cert_verify, LocalFSAdapter.close, LocalFSAdapter.send, PipSession.__init__, PipSession.add_trusted_host; module: session
**utils.py** — function: raise_for_status, response_chunks; 5 imports; module: utils
**xmlrpc.py** — class: PipXmlrpcTransport; 11 imports; method: PipXmlrpcTransport.__init__, PipXmlrpcTransport.request; module: xmlrpc
**check.py** — class: PackageDetails; function: _create_whitelist, _simulate_installation_of, check_install_conflicts, check_package_set, create_package_set_from_installed, warn_legacy_versions_and_specifiers; 18 imports; module: check
**freeze.py** — class: FrozenRequirement, _EditableInfo; function: _format_as_name_version, _get_editable_info, freeze; 24 imports; method: FrozenRequirement.__init__, FrozenRequirement.__str__, FrozenRequirement.from_dist; module: freeze
**__init__.py** — module: __init__
**editable_legacy.py** — function: install_editable; 7 imports; module: editable_legacy
**wheel.py** — class: MissingCallableSuffix, PipScriptMaker, ScriptFile, ZipBackedFile; function: _fs_to_record_path, _install_wheel, _normalized_outrows, _raise_for_invalid_entrypoint, _record_to_fs_path, csv_io_kwargs; 59 imports; method: MissingCallableSuffix.__init__, PipScriptMaker.make, ScriptFile.__init__, ScriptFile.save, ZipBackedFile.__init__, ZipBackedFile._getinfo; module: wheel
**prepare.py** — class: File, RequirementPreparer; function: _check_download_dir, _get_prepared_distribution, get_file_url, get_http_url, unpack_url, unpack_vcs_link; 44 imports; method: File.__init__, RequirementPreparer.__init__, RequirementPreparer._complete_partial_requirements, RequirementPreparer._ensure_link_req_src_dir, RequirementPreparer._fetch_metadata_only, RequirementPreparer._fetch_metadata_using_lazy_wheel; module: prepare; rationale: [FIXME] https://github.com/pypa/pip/issues/11943, [TODO] separate this part out from RequirementPreparer when the v1
**pyproject.py** — function: _is_list_of_str, load_pyproject_toml, make_pyproject_path; 12 imports; module: pyproject
**__init__.py** — class: InstallationResult; function: _validate_requirements, install_given_reqs; 11 imports; method: InstallationResult.__init__, InstallationResult.__repr__; module: __init__
**constructors.py** — class: RequirementParts; function: _get_url_from_path, _looks_like_path, _set_requirement_extras, _strip_extras, check_first_requirement_in_file, convert_extras; 28 imports; method: RequirementParts.__init__; module: constructors; rationale: [TODO] The is_installable_dir test here might not be necessary
**req_file.py** — class: OptionParsingError, ParsedLine, ParsedRequirement, RequirementsFileParser; function: break_args_options, build_parser, expand_env_variables, get_file_content, get_line_parser, handle_line; 26 imports; method: OptionParsingError.__init__, ParsedLine.__init__, ParsedRequirement.__init__, RequirementsFileParser.__init__, RequirementsFileParser._parse_and_recurse, RequirementsFileParser._parse_file; module: req_file; rationale: [FIXME] it would be nice to keep track of the source, [NOTE] mypy disallows assigning to a method, [TODO] handle space after '\'.
**req_install.py** — class: InstallRequirement; function: _has_option, check_invalid_constraint_type, check_legacy_setup_py_options; 61 imports; method: InstallRequirement.__init__, InstallRequirement.__repr__, InstallRequirement.__str__, InstallRequirement._get_archive_name, InstallRequirement._set_requirement, InstallRequirement.archive; module: req_install; rationale: [FIXME] Is there a better place to create the build_dir? (hg and bzr, [TODO] Remove these two variants when packaging is upgraded to
**req_set.py** — class: RequirementSet; 9 imports; method: RequirementSet.__init__, RequirementSet.__repr__, RequirementSet.__str__, RequirementSet.add_named_requirement, RequirementSet.add_unnamed_requirement, RequirementSet.all_requirements; module: req_set
**req_uninstall.py** — class: StashedUninstallPathSet, UninstallPathSet, UninstallPthEntries; function: _script_names, _unique, compact, compress_for_output_listing, compress_for_rename, uninstallation_paths; 29 imports; method: StashedUninstallPathSet.__init__, StashedUninstallPathSet._get_directory_stash, StashedUninstallPathSet._get_file_stash, StashedUninstallPathSet.can_rollback, StashedUninstallPathSet.commit, StashedUninstallPathSet.rollback; module: req_uninstall; rationale: [FIXME] need a test for this elif block
**base.py** — class: BaseResolver; 5 imports; method: BaseResolver.get_installation_order, BaseResolver.resolve; module: base
**resolver.py** — class: Resolver; function: _check_dist_requires_python; 36 imports; method: Resolver.__init__, Resolver._add_requirement_to_set, Resolver._check_skip_installed, Resolver._find_requirement_link, Resolver._get_dist_for, Resolver._is_upgrade_allowed; module: resolver
**base.py** — class: Candidate, Constraint, Requirement; function: _match_link, format_name; 13 imports; method: Candidate.format_for_error, Candidate.get_install_requirement, Candidate.is_editable, Candidate.is_installed, Candidate.iter_dependencies, Candidate.name; module: base
**candidates.py** — class: AlreadyInstalledCandidate, EditableCandidate, ExtrasCandidate, LinkCandidate, RequiresPythonCandidate, _InstallRequirementBackedCandidate; function: _make_install_req_from_dist, as_base_candidate, make_install_req_from_editable, make_install_req_from_link; 30 imports; method: AlreadyInstalledCandidate.__eq__, AlreadyInstalledCandidate.__hash__, AlreadyInstalledCandidate.__init__, AlreadyInstalledCandidate.__repr__, AlreadyInstalledCandidate.__str__, AlreadyInstalledCandidate.format_for_error; module: candidates; rationale: [TODO] Remove this attribute when packaging is upgraded to support the, [TODO] Supply reason based on force_reinstall and upgrade_strategy.
**factory.py** — class: CollectedRootRequirements, Factory; 63 imports; method: Factory.__init__, Factory._fail_if_link_is_unsupported_wheel, Factory._iter_candidates_from_constraints, Factory._iter_explicit_candidates_from_base, Factory._iter_found_candidates, Factory._make_base_candidate_from_link; module: factory; rationale: [TODO] Are there more cases this needs to return True? Editable?, [TODO] Check already installed candidate, and use it if the link and
**found_candidates.py** — class: FoundCandidates; function: _iter_built, _iter_built_with_inserted, _iter_built_with_prepended; 11 imports; method: FoundCandidates.__bool__, FoundCandidates.__getitem__, FoundCandidates.__init__, FoundCandidates.__iter__, FoundCandidates.__len__; module: found_candidates; rationale: [TODO] Remove this block after dropping Python 3.8 support.
**provider.py** — class: PipProvider; function: _get_with_identifier; 18 imports; method: PipProvider.__init__, PipProvider.find_matches, PipProvider.get_dependencies, PipProvider.get_preference, PipProvider.identify, PipProvider.is_backtrack_cause; module: provider; rationale: [HACK] Theoretically we should check whether this identifier is a valid
**reporter.py** — class: PipDebuggingReporter, PipReporter; 7 imports; method: PipDebuggingReporter.adding_requirement, PipDebuggingReporter.ending, PipDebuggingReporter.ending_round, PipDebuggingReporter.pinning, PipDebuggingReporter.rejecting_candidate, PipDebuggingReporter.starting; module: reporter
**requirements.py** — class: ExplicitRequirement, RequiresPythonRequirement, SpecifierRequirement, SpecifierWithoutExtrasRequirement, UnsatisfiableRequirement; 9 imports; method: ExplicitRequirement.__init__, ExplicitRequirement.__repr__, ExplicitRequirement.__str__, ExplicitRequirement.format_for_error, ExplicitRequirement.get_candidate_lookup, ExplicitRequirement.is_satisfied_by; module: requirements
**resolver.py** — class: Resolver; function: _req_set_item_sorter, get_topological_weights; 32 imports; method: Resolver.__init__, Resolver.get_installation_order, Resolver.resolve; module: resolver
**self_outdated_check.py** — class: SelfCheckState, UpgradePrompt; function: _convert_date, _get_current_remote_pip_version, _get_statefile_name, _self_version_check_logic, pip_self_version_check, was_installed_by_pip; 30 imports; method: SelfCheckState.__init__, SelfCheckState.get, SelfCheckState.key, SelfCheckState.set, UpgradePrompt.__rich__; module: self_outdated_check
**_jaraco_text.py** — function: _, _nonblank, drop_comment, join_continuation, yield_lines; 2 imports; module: _jaraco_text
**_log.py** — class: VerboseLogger; function: getLogger, init_logging; 3 imports; method: VerboseLogger.verbose; module: _log
**appdirs.py** — function: _macos_user_config_dir, site_config_dirs, user_cache_dir, user_config_dir; 4 imports; module: appdirs
**compat.py** — function: get_path_uid, has_tls; 5 imports; module: compat
**compatibility_tags.py** — function: _custom_manylinux_platforms, _expand_allowed_platforms, _get_custom_interpreter, _get_custom_platforms, _get_python_version, _mac_platforms; 12 imports; module: compatibility_tags
**datetime.py** — function: today_is_later_than; 1 imports; module: datetime
**deprecation.py** — class: PipDeprecationWarning; function: _showwarning, deprecated, install_warning_logger; 9 imports; module: deprecation; rationale: [NOTE] tests patch this name.
**direct_url_helpers.py** — function: direct_url_as_pep440_direct_reference, direct_url_for_editable, direct_url_from_link; 8 imports; module: direct_url_helpers
**egg_link.py** — function: _egg_link_names, egg_link_path_from_location, egg_link_path_from_sys_path; 9 imports; module: egg_link
**encoding.py** — function: auto_decode; 6 imports; module: encoding
**entrypoints.py** — function: _wrapper, get_best_invocation_for_this_pip, get_best_invocation_for_this_python; 8 imports; module: entrypoints
**filesystem.py** — function: _test_writable_dir_win, adjacent_tmp_file, check_path_owner, directory_size, file_size, find_files; 18 imports; module: filesystem
**filetypes.py** — function: is_archive_file; 2 imports; module: filetypes
**glibc.py** — function: glibc_version_string, glibc_version_string_confstr, glibc_version_string_ctypes, libc_ver; 5 imports; module: glibc
**hashes.py** — class: Hashes, MissingHashes; 13 imports; method: Hashes.__and__, Hashes.__bool__, Hashes.__eq__, Hashes.__hash__, Hashes.__init__, Hashes._raise; module: hashes
**logging.py** — class: BetterRotatingFileHandler, BrokenStdoutLoggingError, ExcludeLoggerFilter, IndentedRenderable, IndentingFormatter, MaxLevelFilter; function: _is_broken_pipe_error, get_indentation, indent_log, setup_logging; 32 imports; method: BetterRotatingFileHandler._open, ExcludeLoggerFilter.filter, IndentedRenderable.__rich_console__, IndentingFormatter.__init__, IndentingFormatter.format, IndentingFormatter.get_message_start; module: logging
**misc.py** — class: ConfiguredBuildBackendHookCaller, HiddenText, StreamWrapper; function: _check_no_input, _get_netloc, _onerror_ignore, _onerror_reraise, _redact_netloc, _transform_url; 48 imports; method: ConfiguredBuildBackendHookCaller.__init__, ConfiguredBuildBackendHookCaller.build_editable, ConfiguredBuildBackendHookCaller.build_sdist, ConfiguredBuildBackendHookCaller.build_wheel, ConfiguredBuildBackendHookCaller.get_requires_for_build_editable, ConfiguredBuildBackendHookCaller.get_requires_for_build_sdist; module: misc
**models.py** — class: KeyBasedCompareMixin; 4 imports; method: KeyBasedCompareMixin.__eq__, KeyBasedCompareMixin.__ge__, KeyBasedCompareMixin.__gt__, KeyBasedCompareMixin.__hash__, KeyBasedCompareMixin.__init__, KeyBasedCompareMixin.__le__; module: models
**packaging.py** — function: check_requires_python, get_requirement, safe_extra; 10 imports; module: packaging
**setuptools_build.py** — function: make_setuptools_bdist_wheel_args, make_setuptools_clean_args, make_setuptools_develop_args, make_setuptools_egg_info_args, make_setuptools_shim_args; 5 imports; module: setuptools_build; rationale: [NOTE] Eventually, we'd want to also -S to the flags here, when we're
**subprocess.py** — function: call_subprocess, format_command_args, make_command, reveal_command_args, runner_with_spinner_message; 20 imports; module: subprocess; rationale: [TODO] Remove `if TYPE_CHECKING` when dropping support for Python 3.7.
**temp_dir.py** — class: AdjacentTempDirectory, TempDirectory, TempDirectoryTypeRegistry, _Default; function: global_tempdir_manager, tempdir_registry; 19 imports; method: AdjacentTempDirectory.__init__, AdjacentTempDirectory._create, AdjacentTempDirectory._generate_names, TempDirectory.__enter__, TempDirectory.__exit__, TempDirectory.__init__; module: temp_dir
**unpacking.py** — function: current_umask, has_leading_dir, is_within_directory, set_extracted_file_to_default_mode_plus_executable, split_leading_dir, unpack_file; 18 imports; module: unpacking; rationale: [FIXME] handle?, [FIXME] magic signatures?
**urls.py** — function: get_url_scheme, path_to_url, url_to_path; 6 imports; module: urls
**virtualenv.py** — function: _get_pyvenv_cfg_lines, _no_global_under_legacy_virtualenv, _no_global_under_venv, _running_under_legacy_virtualenv, _running_under_venv, running_under_virtualenv; 7 imports; module: virtualenv
**wheel.py** — function: check_compatibility, parse_wheel, read_wheel_metadata_file, wheel_dist_info_dir, wheel_metadata, wheel_version; 8 imports; module: wheel
**__init__.py** — 9 imports; module: __init__
**bazaar.py** — class: Bazaar; 13 imports; method: Bazaar.fetch_new, Bazaar.get_base_rev_args, Bazaar.get_remote_url, Bazaar.get_revision, Bazaar.get_url_rev_and_auth, Bazaar.is_commit_id_equal; module: bazaar
**git.py** — class: Git; function: looks_like_hash; 22 imports; method: Git._git_remote_to_pip_url, Git._should_fetch, Git.fetch_new, Git.get_base_rev_args, Git.get_current_branch, Git.get_git_version; module: git; rationale: [NOTE] We do not use splitlines here since that would split on other
**mercurial.py** — class: Mercurial; 16 imports; method: Mercurial.fetch_new, Mercurial.get_base_rev_args, Mercurial.get_remote_url, Mercurial.get_repository_root, Mercurial.get_requirement_revision, Mercurial.get_revision; module: mercurial
**subversion.py** — class: Subversion; 19 imports; method: Subversion.__init__, Subversion._get_svn_url_rev, Subversion.call_vcs_version, Subversion.fetch_new, Subversion.get_base_rev_args, Subversion.get_netloc_and_auth; module: subversion; rationale: [FIXME] should we warn?, [NOTE] taken from setuptools.command.egg_info
**versioncontrol.py** — class: RemoteNotFoundError, RemoteNotValidError, RevOptions, VcsSupport, VersionControl; function: find_path_to_project_root_from_repo_root, is_url, make_vcs_requirement_url; 33 imports; method: RemoteNotValidError.__init__, RevOptions.__init__, RevOptions.__repr__, RevOptions.arg_rev, RevOptions.make_new, RevOptions.to_args; module: versioncontrol; rationale: [TODO] Remove `if TYPE_CHECKING` when dropping support for Python 3.7.
**wheel_builder.py** — function: _build_one, _build_one_inside_env, _clean_one_legacy, _contains_egg_info, _get_cache_dir, _should_build; 31 imports; module: wheel_builder
**__init__.py** — function: vendored; 4 imports; module: __init__
**__init__.py** — 4 imports; module: __init__
**_cmd.py** — function: get_args, get_session, main, setup_logging; 10 imports; module: _cmd
**adapter.py** — class: CacheControlAdapter; 19 imports; method: CacheControlAdapter.__init__, CacheControlAdapter.build_response, CacheControlAdapter.close, CacheControlAdapter.send; module: adapter
**cache.py** — class: BaseCache, DictCache, SeparateBodyBaseCache; 6 imports; method: BaseCache.close, BaseCache.delete, BaseCache.get, BaseCache.set, DictCache.__init__, DictCache.delete; module: cache
**__init__.py** — 3 imports; module: __init__
**file_cache.py** — class: FileCache, SeparateBodyFileCache, _FileCacheMixin; function: _secure_open_write, url_to_file_path; 12 imports; method: FileCache.delete, SeparateBodyFileCache.delete, SeparateBodyFileCache.get_body, SeparateBodyFileCache.set_body, _FileCacheMixin.__init__, _FileCacheMixin._delete; module: file_cache; rationale: [NOTE] This method should not change as some may depend on it.
**redis_cache.py** — class: RedisCache; 6 imports; method: RedisCache.__init__, RedisCache.clear, RedisCache.close, RedisCache.delete, RedisCache.get, RedisCache.set; module: redis_cache
**controller.py** — class: CacheController; function: parse_uri; 17 imports; method: CacheController.__init__, CacheController._cache_set, CacheController._load_from_cache, CacheController._urlnorm, CacheController.cache_response, CacheController.cache_url; module: controller; rationale: [TODO] There is an assumption that the result will be a
**filewrapper.py** — class: CallbackFileWrapper; 7 imports; method: CallbackFileWrapper.__getattr__, CallbackFileWrapper.__init__, CallbackFileWrapper.__is_fp_closed, CallbackFileWrapper._close, CallbackFileWrapper._safe_read, CallbackFileWrapper.read; module: filewrapper; rationale: [TODO] Add some logging here...
**heuristics.py** — class: BaseHeuristic, ExpiresAfter, LastModified, OneDayCache; function: datetime_to_header, expire_after; 13 imports; method: BaseHeuristic.apply, BaseHeuristic.update_headers, BaseHeuristic.warning, ExpiresAfter.__init__, ExpiresAfter.update_headers, ExpiresAfter.warning; module: heuristics
**serialize.py** — class: Serializer; 11 imports; method: Serializer._loads_v0, Serializer._loads_v1, Serializer._loads_v2, Serializer._loads_v3, Serializer._loads_v4, Serializer.dumps; module: serialize
**wrapper.py** — function: CacheControl; 10 imports; module: wrapper
**__init__.py** — 2 imports; module: __init__
**__main__.py** — 3 imports; module: __main__
**core.py** — 8 imports; module: core
**__init__.py** — function: detect, detect_all; 9 imports; module: __init__
**big5freq.py** — module: big5freq
**big5prober.py** — class: Big5Prober; 4 imports; method: Big5Prober.__init__, Big5Prober.charset_name, Big5Prober.language; module: big5prober
**chardistribution.py** — class: Big5DistributionAnalysis, CharDistributionAnalysis, EUCJPDistributionAnalysis, EUCKRDistributionAnalysis, EUCTWDistributionAnalysis, GB2312DistributionAnalysis; 18 imports; method: Big5DistributionAnalysis.__init__, Big5DistributionAnalysis.get_order, CharDistributionAnalysis.__init__, CharDistributionAnalysis.feed, CharDistributionAnalysis.get_confidence, CharDistributionAnalysis.get_order; module: chardistribution
**charsetgroupprober.py** — class: CharSetGroupProber; 6 imports; method: CharSetGroupProber.__init__, CharSetGroupProber.charset_name, CharSetGroupProber.feed, CharSetGroupProber.get_confidence, CharSetGroupProber.language, CharSetGroupProber.reset; module: charsetgroupprober
**charsetprober.py** — class: CharSetProber; 6 imports; method: CharSetProber.__init__, CharSetProber.charset_name, CharSetProber.feed, CharSetProber.filter_high_byte_only, CharSetProber.filter_international_words, CharSetProber.get_confidence; module: charsetprober
**chardetect.py** — function: description_of, main; 7 imports; module: chardetect
**codingstatemachine.py** — class: CodingStateMachine; 3 imports; method: CodingStateMachine.__init__, CodingStateMachine.get_coding_state_machine, CodingStateMachine.get_current_charlen, CodingStateMachine.language, CodingStateMachine.next_state, CodingStateMachine.reset; module: codingstatemachine
**codingstatemachinedict.py** — 3 imports; module: codingstatemachinedict; rationale: [TODO] Remove the else block and TYPE_CHECKING check when dropping support
**cp949prober.py** — class: CP949Prober; 4 imports; method: CP949Prober.__init__, CP949Prober.charset_name, CP949Prober.language; module: cp949prober; rationale: [NOTE] CP949 is a superset of EUC-KR, so the distribution should be
**enums.py** — class: CharacterCategory, InputState, LanguageFilter, MachineState, ProbingState, SequenceLikelihood; 2 imports; method: SequenceLikelihood.get_num_categories; module: enums
**escprober.py** — class: EscCharSetProber; 11 imports; method: EscCharSetProber.__init__, EscCharSetProber.charset_name, EscCharSetProber.feed, EscCharSetProber.get_confidence, EscCharSetProber.language, EscCharSetProber.reset; module: escprober
**escsm.py** — 2 imports; module: escsm
**eucjpprober.py** — class: EUCJPProber; 8 imports; method: EUCJPProber.__init__, EUCJPProber.charset_name, EUCJPProber.feed, EUCJPProber.get_confidence, EUCJPProber.language, EUCJPProber.reset; module: eucjpprober
**euckrfreq.py** — module: euckrfreq
**euckrprober.py** — class: EUCKRProber; 4 imports; method: EUCKRProber.__init__, EUCKRProber.charset_name, EUCKRProber.language; module: euckrprober
**euctwfreq.py** — module: euctwfreq
**euctwprober.py** — class: EUCTWProber; 4 imports; method: EUCTWProber.__init__, EUCTWProber.charset_name, EUCTWProber.language; module: euctwprober
**gb2312freq.py** — module: gb2312freq
**gb2312prober.py** — class: GB2312Prober; 4 imports; method: GB2312Prober.__init__, GB2312Prober.charset_name, GB2312Prober.language; module: gb2312prober
**hebrewprober.py** — class: HebrewProber; 5 imports; method: HebrewProber.__init__, HebrewProber.charset_name, HebrewProber.feed, HebrewProber.is_final, HebrewProber.is_non_final, HebrewProber.language; module: hebrewprober
**jisfreq.py** — module: jisfreq
**johabfreq.py** — module: johabfreq
**johabprober.py** — class: JOHABProber; 4 imports; method: JOHABProber.__init__, JOHABProber.charset_name, JOHABProber.language; module: johabprober
**jpcntx.py** — class: EUCJPContextAnalysis, JapaneseContextAnalysis, SJISContextAnalysis; 3 imports; method: EUCJPContextAnalysis.get_order, JapaneseContextAnalysis.__init__, JapaneseContextAnalysis.feed, JapaneseContextAnalysis.get_confidence, JapaneseContextAnalysis.get_order, JapaneseContextAnalysis.got_enough_data; module: jpcntx
**langbulgarianmodel.py** — 1 imports; module: langbulgarianmodel
**langgreekmodel.py** — 1 imports; module: langgreekmodel
**langhebrewmodel.py** — 1 imports; module: langhebrewmodel
**langhungarianmodel.py** — 1 imports; module: langhungarianmodel
**langrussianmodel.py** — 1 imports; module: langrussianmodel
**langthaimodel.py** — 1 imports; module: langthaimodel
**langturkishmodel.py** — 1 imports; module: langturkishmodel
**latin1prober.py** — class: Latin1Prober; 4 imports; method: Latin1Prober.__init__, Latin1Prober.charset_name, Latin1Prober.feed, Latin1Prober.get_confidence, Latin1Prober.language, Latin1Prober.reset; module: latin1prober
**macromanprober.py** — class: MacRomanProber; 4 imports; method: MacRomanProber.__init__, MacRomanProber.charset_name, MacRomanProber.feed, MacRomanProber.get_confidence, MacRomanProber.language, MacRomanProber.reset; module: macromanprober
**mbcharsetprober.py** — class: MultiByteCharSetProber; 8 imports; method: MultiByteCharSetProber.__init__, MultiByteCharSetProber.feed, MultiByteCharSetProber.get_confidence, MultiByteCharSetProber.reset; module: mbcharsetprober
**mbcsgroupprober.py** — class: MBCSGroupProber; 11 imports; method: MBCSGroupProber.__init__; module: mbcsgroupprober
**mbcssm.py** — 2 imports; module: mbcssm
**languages.py** — class: Language; 3 imports; method: Language.__init__, Language.__repr__; module: languages; rationale: [TODO] Add Ukrainian (KOI8-U)
**resultdict.py** — 3 imports; module: resultdict; rationale: [TODO] Remove the else block and TYPE_CHECKING check when dropping support
**sbcharsetprober.py** — class: SingleByteCharSetModel, SingleByteCharSetProber; 9 imports; method: SingleByteCharSetProber.__init__, SingleByteCharSetProber.charset_name, SingleByteCharSetProber.feed, SingleByteCharSetProber.get_confidence, SingleByteCharSetProber.language, SingleByteCharSetProber.reset; module: sbcharsetprober; rationale: [TODO] Make filter_international_words keep things in self.alphabet, [XXX] This was SYMBOL_CAT_ORDER before, with a value of 250, but
**sbcsgroupprober.py** — class: SBCSGroupProber; 16 imports; method: SBCSGroupProber.__init__; module: sbcsgroupprober; rationale: [TODO] ORDER MATTERS HERE. I changed the order vs what was in master, [TODO] Restore Hungarian encodings (iso-8859-2 and windows-1250), [TODO] See if using ISO-8859-8 Hebrew model works better here, since
**sjisprober.py** — class: SJISProber; 8 imports; method: SJISProber.__init__, SJISProber.charset_name, SJISProber.feed, SJISProber.get_confidence, SJISProber.language, SJISProber.reset; module: sjisprober
**universaldetector.py** — class: UniversalDetector; 18 imports; method: UniversalDetector.__init__, UniversalDetector.charset_probers, UniversalDetector.close, UniversalDetector.feed, UniversalDetector.has_win_bytes, UniversalDetector.input_state; module: universaldetector; rationale: [TODO] This encoding is not supported by Python. Should remove?, [TODO] This encoding is not supported by Python. Should remove?
**utf1632prober.py** — class: UTF1632Prober; 4 imports; method: UTF1632Prober.__init__, UTF1632Prober.approx_16bit_chars, UTF1632Prober.approx_32bit_chars, UTF1632Prober.charset_name, UTF1632Prober.feed, UTF1632Prober.get_confidence; module: utf1632prober
**utf8prober.py** — class: UTF8Prober; 6 imports; method: UTF8Prober.__init__, UTF8Prober.charset_name, UTF8Prober.feed, UTF8Prober.get_confidence, UTF8Prober.language, UTF8Prober.reset; module: utf8prober
**version.py** — module: version
**__init__.py** — 10 imports; module: __init__
**ansi.py** — class: AnsiBack, AnsiCodes, AnsiCursor, AnsiFore, AnsiStyle; function: clear_line, clear_screen, code_to_chars, set_title; method: AnsiCodes.__init__, AnsiCursor.BACK, AnsiCursor.DOWN, AnsiCursor.FORWARD, AnsiCursor.POS, AnsiCursor.UP; module: ansi
**ansitowin32.py** — class: AnsiToWin32, StreamWrapper; 14 imports; method: AnsiToWin32.__init__, AnsiToWin32.call_win32, AnsiToWin32.convert_ansi, AnsiToWin32.convert_osc, AnsiToWin32.extract_params, AnsiToWin32.flush; module: ansitowin32
**initialise.py** — function: _wipe_internal_state_for_tests, colorama_text, deinit, init, just_fix_windows_console, reinit; 4 imports; module: initialise
**__init__.py** — module: __init__
**ansi_test.py** — class: AnsiTest; 7 imports; method: AnsiTest.setUp, AnsiTest.tearDown, AnsiTest.testBackAttributes, AnsiTest.testForeAttributes, AnsiTest.testStyleAttributes; module: ansi_test
**ansitowin32_test.py** — class: AnsiToWin32Test, StreamWrapperTest; 16 imports; method: AnsiToWin32Test.assert_autoresets, AnsiToWin32Test.testCallWin32UsesLookup, AnsiToWin32Test.testExtractParams, AnsiToWin32Test.testInit, AnsiToWin32Test.testStripIsFalseOffWindows, AnsiToWin32Test.testStripIsTrueOnWindows; module: ansitowin32_test
**initialise_test.py** — class: InitTest, JustFixWindowsConsoleTest; 14 imports; method: InitTest.assertNotWrapped, InitTest.assertWrapped, InitTest.setUp, InitTest.tearDown, InitTest.testAtexitRegisteredOnlyOnce, InitTest.testAutoResetChangeable; module: initialise_test
**isatty_test.py** — class: IsattyTest; function: is_a_tty; 10 imports; method: IsattyTest.test_TTY, IsattyTest.test_nonTTY, IsattyTest.test_withPycharm, IsattyTest.test_withPycharmNonTTYOverride, IsattyTest.test_withPycharmNoneOverride, IsattyTest.test_withPycharmStreamWrapped; module: isatty_test
**utils.py** — class: StreamNonTTY, StreamTTY; function: osname, pycharm, replace_by, replace_original_by; 4 imports; method: StreamNonTTY.isatty, StreamTTY.isatty; module: utils
**winterm_test.py** — class: WinTermTest; 11 imports; method: WinTermTest.testBack, WinTermTest.testFore, WinTermTest.testGetAttrs, WinTermTest.testInit, WinTermTest.testResetAll, WinTermTest.testSetConsole; module: winterm_test
**win32.py** — 7 imports; module: win32
**winterm.py** — class: WinColor, WinStyle, WinTerm; function: enable_vt_processing; 2 imports; method: WinTerm.__init__, WinTerm.back, WinTerm.cursor_adjust, WinTerm.erase_line, WinTerm.erase_screen, WinTerm.fore; module: winterm
**__init__.py** — class: DistlibException; 2 imports; module: __init__
**compat.py** — 100 imports; module: compat
**database.py** — class: BaseInstalledDistribution, DependencyGraph, Distribution, DistributionPath, EggInfoDistribution, InstalledDistribution; function: get_dependent_dists, get_required_dists, make_dist, make_graph; 27 imports; method: BaseInstalledDistribution.__init__, BaseInstalledDistribution.get_hash, DependencyGraph.__init__, DependencyGraph.__repr__, DependencyGraph._repr_dist, DependencyGraph.add_distribution; module: database
**index.py** — class: PackageIndex; 20 imports; method: PackageIndex.__init__, PackageIndex._get_pypirc_command, PackageIndex._reader, PackageIndex.check_credentials, PackageIndex.download_file, PackageIndex.encode_request; module: index
**locators.py** — class: AggregatingLocator, DependencyFinder, DirectoryLocator, DistPathLocator, JSONLocator, Locator; function: get_all_distribution_names; 42 imports; method: AggregatingLocator.__init__, AggregatingLocator._get_project, AggregatingLocator._set_scheme, AggregatingLocator.clear_cache, AggregatingLocator.get_distribution_names, DependencyFinder.__init__; module: locators
**manifest.py** — class: Manifest; 11 imports; method: Manifest.__init__, Manifest._exclude_pattern, Manifest._glob_to_re, Manifest._include_pattern, Manifest._parse_directive, Manifest._translate_pattern; module: manifest
**markers.py** — class: Evaluator; function: _get_versions, _is_literal, _is_version_marker, default_context, interpret; 8 imports; method: Evaluator.evaluate; module: markers; rationale: [NOTE] In PEP 345, the micro-language was Python compatible, so the ast
**metadata.py** — class: LegacyMetadata, Metadata, MetadataConflictError, MetadataInvalidError, MetadataMissingError, MetadataUnrecognizedVersionError; function: _best_version, _get_name_and_version, _version2fieldlist; 16 imports; method: LegacyMetadata.__contains__, LegacyMetadata.__delitem__, LegacyMetadata.__getattr__, LegacyMetadata.__getitem__, LegacyMetadata.__init__, LegacyMetadata.__iter__; module: metadata; rationale: [NOTE] MetadataUnrecognizedVersionError does not, [TODO] any other fields wanted
**resources.py** — class: Resource, ResourceBase, ResourceCache, ResourceContainer, ResourceFinder, ZipResourceFinder; function: finder, finder_for_path, register_finder; 15 imports; method: Resource.as_stream, Resource.bytes, Resource.file_path, Resource.size, ResourceBase.__init__, ResourceCache.__init__; module: resources
**scripts.py** — class: ScriptMaker; function: enquote_executable; 19 imports; method: ScriptMaker.__init__, ScriptMaker._build_shebang, ScriptMaker._copy_script, ScriptMaker._get_alternate_executable, ScriptMaker._get_script_text, ScriptMaker._get_shebang; module: scripts
**util.py** — class: CSVBase, CSVReader, CSVWriter, Cache, Configurator, EventMixin; function: _csv_open, _get_external_data, _iglob, _load_pypirc, _store_pypirc, chdir; 49 imports; method: CSVBase.__enter__, CSVBase.__exit__, CSVReader.__init__, CSVReader.__iter__, CSVReader.next, CSVWriter.__init__; module: util
**version.py** — class: LegacyMatcher, LegacyVersion, Matcher, NormalizedMatcher, NormalizedVersion, SemanticMatcher; function: _legacy_key, _match_prefix, _pep_440_key, _semantic_key, _suggest_normalized_version, _suggest_semantic_version; 4 imports; method: LegacyMatcher._match_compatible, LegacyVersion.is_prerelease, LegacyVersion.parse, Matcher.__eq__, Matcher.__hash__, Matcher.__init__; module: version; rationale: [TODO] unintended side-effect on, e.g., "2003.05.09"
**wheel.py** — class: Mounter, Wheel; function: _get_glibc_version, _get_suffixes, _load_dynamic, compatible_tags, is_compatible; 42 imports; method: Mounter.__init__, Mounter.add, Mounter.find_module, Mounter.load_module, Mounter.remove, Wheel.__init__; module: wheel
**__init__.py** — 24 imports; module: __init__
**__main__.py** — 1 imports; module: __main__
**distro.py** — class: InfoDict, LinuxDistribution, VersionDict; function: build_number, codename, distro_release_attr, distro_release_info, id, info; 20 imports; method: LinuxDistribution.__init__, LinuxDistribution.__repr__, LinuxDistribution._debian_version, LinuxDistribution._distro_release_info, LinuxDistribution._lsb_release_info, LinuxDistribution._os_release_info; module: distro; rationale: [NOTE] The idea is to respect order **and** have it set
**__init__.py** — 20 imports; module: __init__
**codec.py** — class: Codec, IncrementalDecoder, IncrementalEncoder, StreamReader, StreamWriter; function: getregentry; 9 imports; method: Codec.decode, Codec.encode, IncrementalDecoder._buffer_decode, IncrementalEncoder._buffer_encode; module: codec
**compat.py** — function: ToASCII, ToUnicode, nameprep; 4 imports; module: compat
**core.py** — class: IDNABidiError, IDNAError, InvalidCodepoint, InvalidCodepointContext; function: _combining_class, _is_script, _punycode, _unot, alabel, check_bidi; 8 imports; module: core
**idnadata.py** — module: idnadata
**intranges.py** — function: _decode_range, _encode_range, intranges_contain, intranges_from_list; 3 imports; module: intranges
**package_data.py** — module: package_data
**uts46data.py** — function: _seg_0, _seg_1, _seg_10, _seg_11, _seg_12, _seg_13; 3 imports; module: uts46data
**__init__.py** — function: pack, packb, unpack; 11 imports; module: __init__
**exceptions.py** — class: BufferFull, ExtraData, FormatError, OutOfData, StackError, UnpackException; method: ExtraData.__init__, ExtraData.__str__; module: exceptions
**ext.py** — class: ExtType, Timestamp; 4 imports; method: ExtType.__new__, Timestamp.__eq__, Timestamp.__hash__, Timestamp.__init__, Timestamp.__ne__, Timestamp.__repr__; module: ext
**fallback.py** — class: Packer, Unpacker; function: _check_type_strict, _get_data_from_buffer, unpackb; 14 imports; method: Packer.__init__, Packer._pack, Packer._pack_array_header, Packer._pack_bin_header, Packer._pack_map_header, Packer._pack_map_pairs; module: fallback
**__about__.py** — module: __about__
**__init__.py** — 8 imports; module: __init__
**_manylinux.py** — class: _ELFFileHeader, _GLibCVersion; function: _get_elf_header, _get_glibc_version, _glibc_version_string, _glibc_version_string_confstr, _glibc_version_string_ctypes, _have_compatible_abi; 15 imports; method: _ELFFileHeader.__init__; module: _manylinux
**_musllinux.py** — class: _MuslVersion; function: _get_musl_version, _parse_ld_musl_from_elf, _parse_musl_version, _read_unpacked, platform_tags; 14 imports; module: _musllinux
**_structures.py** — class: InfinityType, NegativeInfinityType; method: InfinityType.__eq__, InfinityType.__ge__, InfinityType.__gt__, InfinityType.__hash__, InfinityType.__le__, InfinityType.__lt__; module: _structures
**markers.py** — class: InvalidMarker, Marker, Node, Op, Undefined, UndefinedComparison; function: _coerce_parse_result, _eval_op, _evaluate_markers, _format_marker, _get_env, default_environment; 22 imports; method: Marker.__init__, Marker.__repr__, Marker.__str__, Marker.evaluate, Node.__init__, Node.__repr__; module: markers
**requirements.py** — class: InvalidRequirement, Requirement; 21 imports; method: Requirement.__init__, Requirement.__repr__, Requirement.__str__; module: requirements; rationale: [TODO] Can we normalize the name and extra name?, [TODO] Can we test whether something is contained within a requirement?
**specifiers.py** — class: BaseSpecifier, InvalidSpecifier, LegacySpecifier, Specifier, SpecifierSet, _IndividualSpecifier; function: _is_not_suffix, _pad_version, _require_version_compare, _version_split; 20 imports; method: BaseSpecifier.__eq__, BaseSpecifier.__hash__, BaseSpecifier.__str__, BaseSpecifier.contains, BaseSpecifier.filter, BaseSpecifier.prereleases; module: specifiers; rationale: [NOTE] This means that 1.0.dev1 would not be contained in something, [NOTE] This use of all() here means that an empty set of specifiers
**tags.py** — class: Tag; function: _abi3_applies, _cpython_abis, _generic_abi, _generic_platforms, _get_config_var, _linux_platforms; 17 imports; method: Tag.__eq__, Tag.__hash__, Tag.__init__, Tag.__repr__, Tag.__str__, Tag.abi; module: tags; rationale: [TODO] Need to care about 32-bit PPC for ppc64 through 10.2?
**utils.py** — class: InvalidSdistFilename, InvalidWheelFilename; function: canonicalize_name, canonicalize_version, parse_sdist_filename, parse_wheel_filename; 10 imports; module: utils
**version.py** — class: InvalidVersion, LegacyVersion, Version, _BaseVersion; function: _cmpkey, _legacy_cmpkey, _parse_letter_version, _parse_local_version, _parse_version_parts, parse; 15 imports; method: LegacyVersion.__init__, LegacyVersion.__repr__, LegacyVersion.__str__, LegacyVersion.base_version, LegacyVersion.dev, LegacyVersion.epoch; module: version
**__init__.py** — class: ContextualVersionConflict, DefaultProvider, DistInfoDistribution, Distribution, DistributionNotFound, EggInfoDistribution; function: __getstate__, __setstate__, _always_object, _bypass_ensure_directory, _call_aside, _cygwin_patch; 43 imports; method: ContextualVersionConflict.required_by, DefaultProvider._get, DefaultProvider._has, DefaultProvider._isdir, DefaultProvider._listdir, DefaultProvider._register; module: __init__; rationale: [FIXME] 'Distribution.insert_on' is too complex (13), [FIXME] 'ZipProvider._extract_resource' is too complex (12), [TODO] remove this except clause when python/cpython#103632 is fixed.
**__init__.py** — function: _set_platform_dir_class, site_cache_dir, site_cache_path, site_config_dir, site_config_path, site_data_dir; 15 imports; module: __init__
**__main__.py** — function: main; 3 imports; module: __main__
**android.py** — class: Android; function: _android_documents_folder, _android_downloads_folder, _android_folder, _android_music_folder, _android_pictures_folder, _android_videos_folder; 8 imports; method: Android.site_cache_dir, Android.site_config_dir, Android.site_data_dir, Android.user_cache_dir, Android.user_config_dir, Android.user_data_dir; module: android
**api.py** — class: PlatformDirsABC; 9 imports; method: PlatformDirsABC.__init__, PlatformDirsABC._append_app_name_and_version, PlatformDirsABC._optionally_create_directory, PlatformDirsABC.site_cache_dir, PlatformDirsABC.site_cache_path, PlatformDirsABC.site_config_dir; module: api
**macos.py** — class: MacOS; 3 imports; method: MacOS.site_cache_dir, MacOS.site_config_dir, MacOS.site_data_dir, MacOS.user_cache_dir, MacOS.user_config_dir, MacOS.user_data_dir; module: macos
**unix.py** — class: Unix; function: _get_user_dirs_folder, _get_user_media_dir; 7 imports; method: Unix._first_item_as_path_if_multipath, Unix._with_multi_path, Unix.site_cache_dir, Unix.site_cache_path, Unix.site_config_dir, Unix.site_config_path; module: unix
**version.py** — module: version
**windows.py** — class: Windows; function: _pick_get_win_folder, get_win_folder_from_env_vars, get_win_folder_from_registry, get_win_folder_if_csidl_name_not_env_var, get_win_folder_via_ctypes; 9 imports; method: Windows._append_parts, Windows.site_cache_dir, Windows.site_config_dir, Windows.site_data_dir, Windows.user_cache_dir, Windows.user_config_dir; module: windows
**__init__.py** — function: format, highlight, lex; 4 imports; module: __init__
**__main__.py** — 2 imports; module: __main__
**cmdline.py** — class: HelpFormatter; function: _parse_filters, _parse_options, _print_help, _print_list, _print_list_as_json, main; 38 imports; method: HelpFormatter.__init__; module: cmdline
**console.py** — function: ansiformat, colorize, reset_color; module: console
**filter.py** — class: Filter, FunctionFilter; function: apply_filters, simplefilter; method: Filter.__init__, Filter.filter, FunctionFilter.__init__, FunctionFilter.filter; module: filter
**__init__.py** — class: CodeTagFilter, ErrorToken, GobbleFilter, KeywordCaseFilter, NameHighlightFilter, RaiseOnErrorTokenFilter; function: _replace_special, find_filter_class, get_all_filters, get_filter_by_name; 16 imports; method: CodeTagFilter.__init__, CodeTagFilter.filter, GobbleFilter.__init__, GobbleFilter.filter, GobbleFilter.gobble, KeywordCaseFilter.__init__; module: __init__
**formatter.py** — class: Formatter; function: _lookup_style; 3 imports; method: Formatter.__init__, Formatter.format, Formatter.get_style_defs; module: formatter
**__init__.py** — class: _automodule; function: _fn_matches, _load_formatters, find_formatter_class, get_all_formatters, get_formatter_by_name, get_formatter_for_filename; 8 imports; method: _automodule.__getattr__; module: __init__
**_mapping.py** — module: _mapping
**bbcode.py** — class: BBCodeFormatter; 2 imports; method: BBCodeFormatter.__init__, BBCodeFormatter._make_styles, BBCodeFormatter.format_unencoded; module: bbcode
**groff.py** — class: GroffFormatter; 4 imports; method: GroffFormatter.__init__, GroffFormatter._define_colors, GroffFormatter._escape_chars, GroffFormatter._make_styles, GroffFormatter._wrap_line, GroffFormatter._write_lineno; module: groff
**html.py** — class: HtmlFormatter; function: _get_ttype_class, escape_html, webify; 13 imports; method: HtmlFormatter.__init__, HtmlFormatter._create_stylesheet, HtmlFormatter._decodeifneeded, HtmlFormatter._format_lines, HtmlFormatter._get_css_class, HtmlFormatter._get_css_classes; module: html
**img.py** — class: BmpImageFormatter, FontManager, FontNotFound, GifImageFormatter, ImageFormatter, JpgImageFormatter; 13 imports; method: FontManager.__init__, FontManager._create_mac, FontManager._create_nix, FontManager._create_win, FontManager._get_mac_font_path, FontManager._get_nix_font_path; module: img; rationale: [TODO] make sure tab expansion happens earlier in the chain.  It
**irc.py** — class: IRCFormatter; function: ircformat; 12 imports; method: IRCFormatter.__init__, IRCFormatter._write_lineno, IRCFormatter.format_unencoded; module: irc
**latex.py** — class: LatexEmbeddedLexer, LatexFormatter; function: _get_ttype_name, escape_tex; 8 imports; method: LatexEmbeddedLexer.__init__, LatexEmbeddedLexer._filter_to, LatexEmbeddedLexer._find_escape_tokens, LatexEmbeddedLexer._find_safe_escape_tokens, LatexEmbeddedLexer.get_tokens_unprocessed, LatexFormatter.__init__; module: latex; rationale: [TODO] add support for background colors
**other.py** — class: NullFormatter, RawTokenFormatter, TestcaseFormatter; 6 imports; method: NullFormatter.format, RawTokenFormatter.__init__, RawTokenFormatter.format, TestcaseFormatter.__init__, TestcaseFormatter.format; module: other
**pangomarkup.py** — class: PangoMarkupFormatter; function: escape_special_chars; 1 imports; method: PangoMarkupFormatter.__init__, PangoMarkupFormatter.format_unencoded; module: pangomarkup
**rtf.py** — class: RtfFormatter; 3 imports; method: RtfFormatter.__init__, RtfFormatter._escape, RtfFormatter._escape_text, RtfFormatter.format_unencoded; module: rtf
**svg.py** — class: SvgFormatter; function: escape_html; 4 imports; method: SvgFormatter.__init__, SvgFormatter._get_style, SvgFormatter.format_unencoded; module: svg
**terminal.py** — class: TerminalFormatter; 13 imports; method: TerminalFormatter.__init__, TerminalFormatter._get_color, TerminalFormatter._write_lineno, TerminalFormatter.format, TerminalFormatter.format_unencoded; module: terminal
**terminal256.py** — class: EscapeSequence, Terminal256Formatter, TerminalTrueColorFormatter; 3 imports; method: EscapeSequence.__init__, EscapeSequence.color_string, EscapeSequence.escape, EscapeSequence.reset_string, EscapeSequence.true_color_string, Terminal256Formatter.__init__; module: terminal256
**lexer.py** — class: DelegatingLexer, ExtendedRegexLexer, Lexer, LexerContext, LexerMeta, ProfilingRegexLexer; function: bygroups, do_insertions, using; 19 imports; method: DelegatingLexer.__init__, DelegatingLexer.get_tokens_unprocessed, ExtendedRegexLexer.get_tokens_unprocessed, Lexer.__init__, Lexer.__repr__, Lexer.add_filter; module: lexer; rationale: [XXX] cache that somehow, [XXX] cache that somehow
**__init__.py** — class: _automodule; function: _fn_matches, _iter_lexerclasses, _load_lexers, find_lexer_class, find_lexer_class_by_name, find_lexer_class_for_filename; 10 imports; method: _automodule.__getattr__; module: __init__
**_mapping.py** — module: _mapping
**python.py** — class: CythonLexer, DgLexer, NumPyLexer, Python2Lexer, Python2TracebackLexer, PythonConsoleLexer; 29 imports; method: NumPyLexer.analyse_text, NumPyLexer.get_tokens_unprocessed, Python2Lexer.analyse_text, Python2Lexer.innerstring_rules, PythonConsoleLexer.__init__, PythonLexer.analyse_text; module: python
**modeline.py** — function: get_filetype_from_buffer, get_filetype_from_line; 1 imports; module: modeline
**plugin.py** — function: find_plugin_filters, find_plugin_formatters, find_plugin_lexers, find_plugin_styles, iter_entry_points; 3 imports; module: plugin
**regexopt.py** — function: make_charset, regex_opt, regex_opt_inner; 5 imports; module: regexopt
**scanner.py** — class: EndOfText, Scanner; 1 imports; method: Scanner.__init__, Scanner.__repr__, Scanner.check, Scanner.eos, Scanner.get_char, Scanner.scan; module: scanner
**sphinxext.py** — class: PygmentsDoc; function: setup; 9 imports; method: PygmentsDoc.document_filters, PygmentsDoc.document_formatters, PygmentsDoc.document_lexers, PygmentsDoc.document_lexers_overview, PygmentsDoc.run; module: sphinxext
**style.py** — class: Style, StyleMeta; 2 imports; method: StyleMeta.__iter__, StyleMeta.__len__, StyleMeta.__new__, StyleMeta.list_styles, StyleMeta.style_for_token, StyleMeta.styles_token; module: style
**__init__.py** — function: get_all_styles, get_style_by_name; 2 imports; module: __init__
**token.py** — class: _TokenType; function: is_token_subtype, string_to_tokentype; method: _TokenType.__contains__, _TokenType.__copy__, _TokenType.__deepcopy__, _TokenType.__getattr__, _TokenType.__init__, _TokenType.__repr__; module: token
**unistring.py** — function: _handle_runs, allexcept, combine; 1 imports; module: unistring
**util.py** — class: ClassNotFound, Future, OptionError, UnclosingTextIOWrapper; function: docstring_headline, doctype_matches, duplicates_removed, format_lines, get_bool_opt, get_choice_opt; 3 imports; method: Future.get, UnclosingTextIOWrapper.close; module: util
**__init__.py** — class: version_info; 17 imports; method: version_info.__repr__, version_info.__str__, version_info.__version__; module: __init__
**actions.py** — class: OnlyOnce; function: matchOnlyAtCol, match_only_at_col, removeQuotes, remove_quotes, replaceWith, replace_with; 4 imports; method: OnlyOnce.__call__, OnlyOnce.__init__, OnlyOnce.reset; module: actions
**common.py** — class: pyparsing_common; 5 imports; method: pyparsing_common.convert_to_date, pyparsing_common.convert_to_datetime, pyparsing_common.strip_html_tags; module: common
**core.py** — class: And, AtLineStart, AtStringStart, CaselessKeyword, CaselessLiteral, Char; function: _default_exception_debug_action, _default_start_debug_action, _default_success_debug_action, _should_enable_warnings, _trim_arity, autoname_elements; 49 imports; method: And.__iadd__, And.__init__, And._checkRecursion, And._generateDefaultName, And.parseImpl, And.streamline; module: core
**__init__.py** — class: AnnotatedItem, ConverterState, EachItem, EditablePartial, ElementState; function: _apply_diagram_item_enhancements, _should_vertical, _to_diagram_element, _visible_exprs, _worth_extracting, railroad_to_html; 14 imports; method: AnnotatedItem.__init__, ConverterState.__contains__, ConverterState.__delitem__, ConverterState.__getitem__, ConverterState.__init__, ConverterState.__setitem__; module: __init__; rationale: [NOTE] ideally this would be a dataclass, but we're supporting Python 3.5+ so we can't , [NOTE] this should be a dataclass, but we have to support Python 3.5
**exceptions.py** — class: ExceptionWordUnicode, ParseBaseException, ParseException, ParseFatalException, ParseSyntaxException, RecursiveGrammarException; 11 imports; method: ParseBaseException.__init__, ParseBaseException.__repr__, ParseBaseException.__str__, ParseBaseException._from_exception, ParseBaseException.col, ParseBaseException.column; module: exceptions
**helpers.py** — class: OpAssoc; function: _makeTags, countedArray, counted_array, delimitedList, delimited_list, dictOf; 10 imports; module: helpers
**results.py** — class: ParseResults, _ParseResultsWithOffset; 12 imports; method: ParseResults.__add__, ParseResults.__bool__, ParseResults.__contains__, ParseResults.__delitem__, ParseResults.__dir__, ParseResults.__getattr__; module: results
**testing.py** — class: pyparsing_test; 7 imports; method: pyparsing_test.with_line_numbers; module: testing
**unicode.py** — class: _lazyclassproperty, pyparsing_unicode, unicode_set; 6 imports; method: _lazyclassproperty.__get__, _lazyclassproperty.__init__, unicode_set._chars_for_ranges, unicode_set.alphanums, unicode_set.alphas, unicode_set.identbodychars; module: unicode
**util.py** — class: LRUMemo, UnboundedMemo, _FifoCache, _UnboundedCache, __config_flags; function: _collapse_string_to_ranges, _escape_regex_range_chars, _flatten, _make_synonym_function, col, line; 13 imports; method: LRUMemo.__delitem__, LRUMemo.__getitem__, LRUMemo.__init__, LRUMemo.__setitem__, LRUMemo.clear, UnboundedMemo.__delitem__; module: util
**__init__.py** — 7 imports; module: __init__
**_compat.py** — 3 imports; module: _compat
**_impl.py** — class: BackendInvalid, BackendUnavailable, BuildBackendHookCaller, HookMissing, UnsupportedOperation; function: default_subprocess_runner, norm_and_check, quiet_subprocess_runner, read_json, write_json; 11 imports; method: BackendInvalid.__init__, BackendUnavailable.__init__, BuildBackendHookCaller.__init__, BuildBackendHookCaller._call_hook, BuildBackendHookCaller._supported_features, BuildBackendHookCaller.build_editable; module: _impl
**__init__.py** — 1 imports; module: __init__
**_in_process.py** — class: BackendInvalid, BackendUnavailable, GotUnsupportedOperation, HookMissing, _DummyException; function: _build_backend, _dist_info_files, _find_already_built_wheel, _get_wheel_metadata_from_wheel, _supported_features, build_editable; 11 imports; method: BackendInvalid.__init__, BackendUnavailable.__init__, GotUnsupportedOperation.__init__, HookMissing.__init__; module: _in_process
**__init__.py** — function: _check_cryptography, check_compatibility; 47 imports; module: __init__; rationale: [NOTE] This logic prevents upgrading cryptography on Windows, if imported
**__version__.py** — module: __version__
**_internal_utils.py** — function: to_native_string, unicode_is_ascii; 2 imports; module: _internal_utils
**adapters.py** — class: BaseAdapter, HTTPAdapter; 43 imports; method: BaseAdapter.__init__, BaseAdapter.close, BaseAdapter.send, HTTPAdapter.__getstate__, HTTPAdapter.__init__, HTTPAdapter.__setstate__; module: adapters; rationale: [TODO] Remove this in 3.0.0: see #2811
**api.py** — function: delete, get, head, options, patch, post; 1 imports; module: api
**auth.py** — class: AuthBase, HTTPBasicAuth, HTTPDigestAuth, HTTPProxyAuth; function: _basic_auth_str; 13 imports; method: AuthBase.__call__, HTTPBasicAuth.__call__, HTTPBasicAuth.__eq__, HTTPBasicAuth.__init__, HTTPBasicAuth.__ne__, HTTPDigestAuth.__call__; module: auth
**certs.py** — 2 imports; module: certs
**compat.py** — 26 imports; module: compat; rationale: [NOTE] We've patched out simplejson support in pip because it prevents
**cookies.py** — class: CookieConflictError, MockRequest, MockResponse, RequestsCookieJar; function: _copy_cookie_jar, cookiejar_from_dict, create_cookie, extract_cookies_to_jar, get_cookie_header, merge_cookies; 11 imports; method: MockRequest.__init__, MockRequest.add_header, MockRequest.add_unredirected_header, MockRequest.get_full_url, MockRequest.get_header, MockRequest.get_host; module: cookies
**exceptions.py** — class: ChunkedEncodingError, ConnectTimeout, ConnectionError, ContentDecodingError, FileModeWarning, HTTPError; 2 imports; method: JSONDecodeError.__init__, RequestException.__init__; module: exceptions
**help.py** — function: _implementation, info, main; 11 imports; module: help
**hooks.py** — function: default_hooks, dispatch_hook; module: hooks; rationale: [TODO] response is the only one
**models.py** — class: PreparedRequest, Request, RequestEncodingMixin, RequestHooksMixin, Response; 52 imports; method: PreparedRequest.__init__, PreparedRequest.__repr__, PreparedRequest._get_idna_encoded_host, PreparedRequest.copy, PreparedRequest.prepare, PreparedRequest.prepare_auth; module: models
**packages.py** — 1 imports; module: packages
**sessions.py** — class: Session, SessionRedirectMixin; function: merge_hooks, merge_setting, session; 38 imports; method: Session.__enter__, Session.__exit__, Session.__getstate__, Session.__init__, Session.__setstate__, Session.close; module: sessions
**status_codes.py** — function: _init; 1 imports; module: status_codes
**structures.py** — class: CaseInsensitiveDict, LookupDict; 3 imports; method: CaseInsensitiveDict.__delitem__, CaseInsensitiveDict.__eq__, CaseInsensitiveDict.__getitem__, CaseInsensitiveDict.__init__, CaseInsensitiveDict.__iter__, CaseInsensitiveDict.__len__; module: structures
**utils.py** — function: _parse_content_type_header, _validate_header_part, add_dict_to_cookiejar, address_in_network, atomic_open, check_header_validity; 43 imports; module: utils
**__init__.py** — 9 imports; module: __init__
**collections_abc.py** — 4 imports; module: collections_abc
**providers.py** — class: AbstractProvider, AbstractResolver; method: AbstractProvider.find_matches, AbstractProvider.get_dependencies, AbstractProvider.get_preference, AbstractProvider.identify, AbstractProvider.is_satisfied_by, AbstractResolver.__init__; module: providers
**reporters.py** — class: BaseReporter; method: BaseReporter.adding_requirement, BaseReporter.ending, BaseReporter.ending_round, BaseReporter.pinning, BaseReporter.rejecting_candidate, BaseReporter.resolving_conflicts; module: reporters
**resolvers.py** — class: Criterion, InconsistentCandidate, RequirementsConflicted, Resolution, ResolutionError, ResolutionImpossible; function: _build_result, _has_route_to_root; 7 imports; method: Criterion.__init__, Criterion.__repr__, Criterion.iter_parent, Criterion.iter_requirement, InconsistentCandidate.__init__, InconsistentCandidate.__str__; module: resolvers
**structs.py** — class: DirectedGraph, IteratorMapping, _FactoryIterableView, _SequenceIterableView; function: build_iter_view; 2 imports; method: DirectedGraph.__contains__, DirectedGraph.__init__, DirectedGraph.__iter__, DirectedGraph.__len__, DirectedGraph.add, DirectedGraph.connect; module: structs; rationale: [XXX] Python 2., [XXX] Python 2., [XXX] Python 2.
**__init__.py** — function: get_console, inspect, print, print_json, reconfigure; 11 imports; module: __init__
**__main__.py** — class: ColorBox; function: make_test_card; 19 imports; method: ColorBox.__rich_console__, ColorBox.__rich_measure__; module: __main__
**_cell_widths.py** — module: _cell_widths
**_emoji_codes.py** — module: _emoji_codes
**_emoji_replace.py** — function: _emoji_replace; 5 imports; module: _emoji_replace
**_export_format.py** — module: _export_format
**_extension.py** — function: load_ipython_extension; 3 imports; module: _extension
**_fileno.py** — function: get_fileno; 3 imports; module: _fileno
**_inspect.py** — class: Inspect; function: _first_paragraph, get_object_types_mro, get_object_types_mro_as_strings, is_object_one_of_types; 25 imports; method: Inspect.__init__, Inspect.__rich__, Inspect._get_formatted_doc, Inspect._get_signature, Inspect._make_title, Inspect._render; module: _inspect
**_log_render.py** — class: LogRender; 15 imports; method: LogRender.__call__, LogRender.__init__; module: _log_render
**_loop.py** — function: loop_first, loop_first_last, loop_last; 3 imports; module: _loop
**_null_file.py** — class: NullFile; 7 imports; method: NullFile.__enter__, NullFile.__exit__, NullFile.__iter__, NullFile.__next__, NullFile.close, NullFile.fileno; module: _null_file
**_palettes.py** — 1 imports; module: _palettes
**_pick.py** — function: pick_bool; 1 imports; module: _pick
**_ratio.py** — class: Edge; function: ratio_distribute, ratio_reduce, ratio_resolve; 10 imports; module: _ratio
**_spinners.py** — module: _spinners
**_stack.py** — class: Stack; 2 imports; method: Stack.push, Stack.top; module: _stack
**_timer.py** — function: timer; 3 imports; module: _timer
**_win32_console.py** — class: CONSOLE_CURSOR_INFO, CONSOLE_SCREEN_BUFFER_INFO, LegacyWindowsError, LegacyWindowsTerm, WindowsCoordinates; function: FillConsoleOutputAttribute, FillConsoleOutputCharacter, GetConsoleCursorInfo, GetConsoleMode, GetConsoleScreenBufferInfo, GetStdHandle; 14 imports; method: LegacyWindowsTerm.__init__, LegacyWindowsTerm._get_cursor_size, LegacyWindowsTerm.cursor_position, LegacyWindowsTerm.erase_end_of_line, LegacyWindowsTerm.erase_line, LegacyWindowsTerm.erase_start_of_line; module: _win32_console
**_windows.py** — class: WindowsConsoleFeatures; 10 imports; module: _windows
**_windows_renderer.py** — function: legacy_windows_render; 9 imports; module: _windows_renderer
**_wrap.py** — function: divide_line, words; 8 imports; module: _wrap
**abc.py** — class: RichRenderable; 2 imports; method: RichRenderable.__subclasshook__; module: abc
**align.py** — class: Align, VerticalCenter; 20 imports; method: Align.__init__, Align.__repr__, Align.__rich_console__, Align.__rich_measure__, Align.center, Align.left; module: align
**ansi.py** — class: AnsiDecoder, _AnsiToken; function: _ansi_tokenize; 13 imports; method: AnsiDecoder.__init__, AnsiDecoder.decode, AnsiDecoder.decode_line; module: ansi
**bar.py** — class: Bar; 10 imports; method: Bar.__init__, Bar.__repr__, Bar.__rich_console__, Bar.__rich_measure__; module: bar
**box.py** — class: Box; 14 imports; method: Box.__init__, Box.__repr__, Box.__str__, Box.get_bottom, Box.get_plain_headed_box, Box.get_row; module: box
**cells.py** — function: _get_codepoint_cell_size, cached_cell_len, cell_len, chop_cells, get_character_cell_size, set_cell_size; 5 imports; module: cells; rationale: [TODO] This is inefficient, [TODO] This might not work with CWJ type characters
**color.py** — class: Color, ColorParseError, ColorSystem, ColorType; function: blend_rgb, parse_rgb_hex; 21 imports; method: Color.__rich__, Color.__rich_repr__, Color.default, Color.downgrade, Color.from_ansi, Color.from_rgb; module: color
**color_triplet.py** — class: ColorTriplet; 2 imports; method: ColorTriplet.hex, ColorTriplet.normalized, ColorTriplet.rgb; module: color_triplet
**columns.py** — class: Columns; 22 imports; method: Columns.__init__, Columns.__rich_console__, Columns.add_renderable; module: columns
**console.py** — class: Capture, CaptureError, Console, ConsoleDimensions, ConsoleOptions, ConsoleRenderable; function: _is_jupyter, _svg_hash, detect_legacy_windows, get_windows_console_features, group; 92 imports; method: Capture.__enter__, Capture.__exit__, Capture.__init__, Capture.get, Console.__enter__, Console.__exit__; module: console
**constrain.py** — class: Constrain; 8 imports; method: Constrain.__init__, Constrain.__rich_console__, Constrain.__rich_measure__; module: constrain
**containers.py** — class: Lines, Renderables; 18 imports; method: Lines.__getitem__, Lines.__init__, Lines.__iter__, Lines.__len__, Lines.__repr__, Lines.__rich_console__; module: containers
**control.py** — class: Control; function: escape_control_codes, strip_control_codes; 17 imports; method: Control.__init__, Control.__rich_console__, Control.__str__, Control.alt_screen, Control.bell, Control.clear; module: control
**default_styles.py** — 7 imports; module: default_styles
**diagnose.py** — function: report; 7 imports; module: diagnose
**emoji.py** — class: Emoji, NoEmoji; 16 imports; method: Emoji.__init__, Emoji.__repr__, Emoji.__rich_console__, Emoji.__str__, Emoji.replace; module: emoji
**errors.py** — class: ConsoleError, LiveError, MarkupError, MissingStyle, NoAltScreen, NotRenderableError; module: errors
**file_proxy.py** — class: FileProxy; 8 imports; method: FileProxy.__getattr__, FileProxy.__init__, FileProxy.fileno, FileProxy.flush, FileProxy.rich_proxied_file, FileProxy.write; module: file_proxy
**filesize.py** — function: _to_str, decimal, pick_unit_and_suffix; 4 imports; module: filesize
**highlighter.py** — class: Highlighter, ISO8601Highlighter, JSONHighlighter, NullHighlighter, RegexHighlighter, ReprHighlighter; function: _combine_regex; 9 imports; method: Highlighter.__call__, Highlighter.highlight, JSONHighlighter.highlight, NullHighlighter.highlight, RegexHighlighter.highlight; module: highlighter
**json.py** — class: JSON; 13 imports; method: JSON.__init__, JSON.__rich__, JSON.from_data; module: json
**jupyter.py** — class: JupyterMixin, JupyterRenderable; function: _render_segments, display, print; 11 imports; method: JupyterMixin._repr_mimebundle_, JupyterRenderable.__init__, JupyterRenderable._repr_mimebundle_; module: jupyter
**layout.py** — class: ColumnSplitter, Layout, LayoutError, LayoutRender, NoSplitter, RowSplitter; 32 imports; method: ColumnSplitter.divide, ColumnSplitter.get_tree_icon, Layout.__getitem__, Layout.__init__, Layout.__rich_console__, Layout.__rich_repr__; module: layout
**live.py** — class: Live, _RefreshThread; 39 imports; method: Live.__enter__, Live.__exit__, Live.__init__, Live._disable_redirect_io, Live._enable_redirect_io, Live.get_renderable; module: live
**live_render.py** — class: LiveRender; 15 imports; method: LiveRender.__init__, LiveRender.__rich_console__, LiveRender.position_cursor, LiveRender.restore_cursor, LiveRender.set_renderable; module: live_render
**logging.py** — class: RichHandler; 23 imports; method: RichHandler.__init__, RichHandler.emit, RichHandler.get_level_text, RichHandler.render, RichHandler.render_message; module: logging
**markup.py** — class: Tag; function: _parse, escape, render; 19 imports; method: Tag.__str__, Tag.markup; module: markup
**measure.py** — class: Measurement; function: measure_renderables; 12 imports; method: Measurement.clamp, Measurement.get, Measurement.normalize, Measurement.span, Measurement.with_maximum, Measurement.with_minimum; module: measure
**padding.py** — class: Padding; 15 imports; method: Padding.__init__, Padding.__repr__, Padding.__rich_console__, Padding.__rich_measure__, Padding.indent, Padding.unpack; module: padding
**pager.py** — class: Pager, SystemPager; 5 imports; method: Pager.show, SystemPager._pager, SystemPager.show; module: pager
**palette.py** — class: Palette; 15 imports; method: Palette.__getitem__, Palette.__init__, Palette.__rich__, Palette.match; module: palette
**panel.py** — class: Panel; 21 imports; method: Panel.__init__, Panel.__rich_console__, Panel.__rich_measure__, Panel._subtitle, Panel._title, Panel.fit; module: panel
**pretty.py** — class: Node, Pretty, _Line; function: _get_attr_fields, _get_braces_for_array, _get_braces_for_defaultdict, _has_default_namedtuple_repr, _ipy_display_hook, _is_attr_object; 53 imports; method: Node.__str__, Node.check_length, Node.iter_tokens, Node.render, Pretty.__init__, Pretty.__rich_console__; module: pretty
**progress.py** — class: BarColumn, DownloadColumn, FileSizeColumn, MofNCompleteColumn, Progress, ProgressColumn; function: open, track, wrap_file; 63 imports; method: BarColumn.__init__, BarColumn.render, DownloadColumn.__init__, DownloadColumn.render, FileSizeColumn.render, MofNCompleteColumn.__init__; module: progress
**progress_bar.py** — class: ProgressBar; 18 imports; method: ProgressBar.__init__, ProgressBar.__repr__, ProgressBar.__rich_console__, ProgressBar.__rich_measure__, ProgressBar._get_pulse_segments, ProgressBar._render_pulse; module: progress_bar
**prompt.py** — class: Confirm, FloatPrompt, IntPrompt, InvalidResponse, Prompt, PromptBase; 13 imports; method: Confirm.process_response, Confirm.render_default, InvalidResponse.__init__, InvalidResponse.__rich__, PromptBase.__call__, PromptBase.__init__; module: prompt
**protocol.py** — function: is_renderable, rich_cast; 6 imports; module: protocol
**region.py** — class: Region; 1 imports; module: region
**repr.py** — class: ReprError; function: auto, rich_repr; 13 imports; module: repr
**rule.py** — class: Rule; 13 imports; method: Rule.__init__, Rule.__repr__, Rule.__rich_console__, Rule.__rich_measure__, Rule._rule_line; module: rule
**scope.py** — function: render_scope; 13 imports; module: scope
**screen.py** — class: Screen; 11 imports; method: Screen.__init__, Screen.__rich_console__; module: screen
**segment.py** — class: ControlType, Segment, SegmentLines, Segments; 29 imports; method: Segment.__bool__, Segment.__rich_repr__, Segment._split_cells, Segment.adjust_line_length, Segment.align_bottom, Segment.align_middle; module: segment
**spinner.py** — class: Spinner; 18 imports; method: Spinner.__init__, Spinner.__rich_console__, Spinner.__rich_measure__, Spinner.render, Spinner.update; module: spinner
**status.py** — class: Status; 10 imports; method: Status.__enter__, Status.__exit__, Status.__init__, Status.__rich__, Status.console, Status.renderable; module: status
**style.py** — class: Style, StyleStack, _Bit; 22 imports; method: Style.__add__, Style.__bool__, Style.__eq__, Style.__hash__, Style.__init__, Style.__ne__; module: style
**styled.py** — class: Styled; 10 imports; method: Styled.__init__, Styled.__rich_console__, Styled.__rich_measure__; module: styled
**syntax.py** — class: ANSISyntaxTheme, PygmentsSyntaxTheme, Syntax, SyntaxTheme, _SyntaxHighlightRange; function: _get_code_index_for_syntax_position; 55 imports; method: ANSISyntaxTheme.__init__, ANSISyntaxTheme.get_background_style, ANSISyntaxTheme.get_style_for_token, PygmentsSyntaxTheme.__init__, PygmentsSyntaxTheme.get_background_style, PygmentsSyntaxTheme.get_style_for_token; module: syntax
**table.py** — class: Column, Row, Table, _Cell; 40 imports; method: Column.cells, Column.copy, Column.flexible, Table.__init__, Table.__rich_console__, Table.__rich_measure__; module: table
**terminal_theme.py** — class: TerminalTheme; 5 imports; method: TerminalTheme.__init__; module: terminal_theme
**text.py** — class: Span, Text; 37 imports; method: Span.__bool__, Span.__repr__, Span.move, Span.right_crop, Span.split, Text.__add__; module: text; rationale: [TODO] This is a little inefficient, it is only used by full justify
**theme.py** — class: Theme, ThemeStack, ThemeStackError; 9 imports; method: Theme.__init__, Theme.config, Theme.from_file, Theme.read, ThemeStack.__init__, ThemeStack.pop_theme; module: theme
**themes.py** — 2 imports; module: themes
**traceback.py** — class: Frame, PathHighlighter, Stack, Trace, Traceback, _SyntaxError; function: install; 48 imports; method: Traceback.__init__, Traceback.__rich_console__, Traceback._guess_lexer, Traceback._render_stack, Traceback._render_syntax_error, Traceback.extract; module: traceback
**tree.py** — class: Tree; 22 imports; method: Tree.__init__, Tree.__rich_console__, Tree.__rich_measure__, Tree.add; module: tree
**six.py** — class: Module_six_moves_urllib, Module_six_moves_urllib_error, Module_six_moves_urllib_parse, Module_six_moves_urllib_request, Module_six_moves_urllib_response, Module_six_moves_urllib_robotparser; function: _add_doc, _import_module, add_metaclass, add_move, assertCountEqual, assertNotRegex; 10 imports; method: Module_six_moves_urllib.__dir__, MovedAttribute.__init__, MovedAttribute._resolve, MovedModule.__getattr__, MovedModule.__init__, MovedModule._resolve; module: six
**__init__.py** — class: AttemptManager, BaseAction, BaseRetrying, DoAttempt, DoSleep, Future; function: _first_set, retry; 53 imports; method: AttemptManager.__enter__, AttemptManager.__exit__, AttemptManager.__init__, BaseAction.__repr__, BaseAction.__str__, BaseRetrying.__call__; module: __init__
**_asyncio.py** — class: AsyncRetrying; 9 imports; method: AsyncRetrying.__aiter__, AsyncRetrying.__anext__, AsyncRetrying.__call__, AsyncRetrying.__init__, AsyncRetrying.__iter__, AsyncRetrying.wraps; module: _asyncio
**_utils.py** — function: find_ordinal, get_callback_name, to_ordinal, to_seconds; 3 imports; module: _utils
**after.py** — function: after_log, after_nothing; 4 imports; module: after
**before.py** — function: before_log, before_nothing; 4 imports; module: before
**before_sleep.py** — function: before_sleep_log, before_sleep_nothing; 4 imports; module: before_sleep
**nap.py** — class: sleep_using_event; function: sleep; 3 imports; method: sleep_using_event.__call__, sleep_using_event.__init__; module: nap
**retry.py** — class: _retry_always, _retry_never, retry_all, retry_any, retry_base, retry_if_exception; 4 imports; method: _retry_always.__call__, _retry_never.__call__, retry_all.__call__, retry_all.__init__, retry_any.__call__, retry_any.__init__; module: retry
**stop.py** — class: _stop_never, stop_after_attempt, stop_after_delay, stop_all, stop_any, stop_base; 5 imports; method: _stop_never.__call__, stop_after_attempt.__call__, stop_after_attempt.__init__, stop_after_delay.__call__, stop_after_delay.__init__, stop_all.__call__; module: stop
**tornadoweb.py** — class: TornadoRetrying; 8 imports; method: TornadoRetrying.__call__, TornadoRetrying.__init__; module: tornadoweb
**wait.py** — class: wait_base, wait_chain, wait_combine, wait_exponential, wait_exponential_jitter, wait_fixed; 5 imports; method: wait_base.__add__, wait_base.__call__, wait_base.__radd__, wait_chain.__call__, wait_chain.__init__, wait_combine.__call__; module: wait
**__init__.py** — 3 imports; module: __init__
**_parser.py** — class: Flags, NestedDict, Output, TOMLDecodeError; function: create_dict_rule, create_list_rule, is_unicode_scalar_value, key_value_rule, load, loads; 16 imports; method: Flags.__init__, Flags.add_pending, Flags.finalize_pending, Flags.is_, Flags.set, Flags.unset_all; module: _parser; rationale: [IMPORTANT] order conditions based on speed of checking and likelihood
**_re.py** — function: cached_tz, match_to_datetime, match_to_localtime, match_to_number; 11 imports; module: _re
**_types.py** — 3 imports; module: _types
**__init__.py** — 4 imports; module: __init__
**_api.py** — class: SSLContext; function: _verify_peercerts, extract_from_ssl, inject_into_ssl; 18 imports; method: SSLContext.__class__, SSLContext.__init__, SSLContext.cert_store_stats, SSLContext.check_hostname, SSLContext.get_ca_certs, SSLContext.get_ciphers; module: _api
**_macos.py** — class: CFConst; function: _bytes_to_cf_data_ref, _bytes_to_cf_string, _cf_string_ref_to_str, _configure_context, _der_certs_to_cf_cert_array, _handle_osstatus; 16 imports; module: _macos; rationale: [TODO] Not sure if we need the SecTrustResultType for anything?
**_openssl.py** — function: _capath_contains_certs, _configure_context, _verify_peercerts_impl; 5 imports; module: _openssl
**_ssl_constants.py** — function: _set_ssl_context_verify_mode; 3 imports; module: _ssl_constants
**_windows.py** — class: CERT_CHAIN_CONTEXT, CERT_CHAIN_ELEMENT, CERT_CHAIN_ENGINE_CONFIG, CERT_CHAIN_PARA, CERT_CHAIN_POLICY_PARA, CERT_CHAIN_POLICY_STATUS; function: _configure_context, _get_and_verify_cert_chain, _handle_win_error, _verify_peercerts_impl, _verify_using_custom_ca_certs; 28 imports; module: _windows
**typing_extensions.py** — class: TypeVar, _DefaultMixin, _ExtensionsSpecialForm, _Sentinel, _SpecialForm, _TypeVarLikeMeta; function: IntVar, _caller, _check_generic, _collect_type_vars, _concatenate_getitem, _ensure_subclassable; 13 imports; method: TypeVar.__init_subclass__, TypeVar.__new__, _ExtensionsSpecialForm.__repr__, _Sentinel.__repr__, _SpecialForm.__call__, _SpecialForm.__getattr__; module: typing_extensions; rationale: [NOTE] DO NOT call super() in any methods in this class
**__init__.py** — function: add_stderr_logger, disable_warnings; 19 imports; module: __init__
**_collections.py** — class: HTTPHeaderDict, RecentlyUsedContainer; 11 imports; method: HTTPHeaderDict.__contains__, HTTPHeaderDict.__delitem__, HTTPHeaderDict.__eq__, HTTPHeaderDict.__getitem__, HTTPHeaderDict.__init__, HTTPHeaderDict.__iter__; module: _collections
**_version.py** — module: _version
**connection.py** — class: DummyConnection, HTTPConnection, HTTPSConnection; function: _get_default_user_agent, _match_hostname; 31 imports; method: HTTPConnection.__init__, HTTPConnection._is_using_tunnel, HTTPConnection._new_conn, HTTPConnection._prepare_conn, HTTPConnection.connect, HTTPConnection.host; module: connection; rationale: [TODO] Fix tunnel so it doesn't depend on self.sock state.
**connectionpool.py** — class: ConnectionPool, HTTPConnectionPool, HTTPSConnectionPool; function: _close_pool_connections, _normalize_host, connection_from_url; 49 imports; method: ConnectionPool.__enter__, ConnectionPool.__exit__, ConnectionPool.__init__, ConnectionPool.__str__, ConnectionPool.close, HTTPConnectionPool.__init__; module: connectionpool; rationale: [TODO] Add optional support for socket.gethostbyname checking.
**_appengine_environ.py** — function: is_appengine, is_appengine_sandbox, is_local_appengine, is_prod_appengine, is_prod_appengine_mvms; 1 imports; module: _appengine_environ
**bindings.py** — class: CFConst, SecurityConst; function: load_cdll; 16 imports; module: bindings
**low_level.py** — function: _assert_no_error, _build_tls_unknown_ca_alert, _cert_array_from_pem, _cf_data_from_bytes, _cf_dictionary_from_tuples, _cf_string_to_unicode; 11 imports; module: low_level
**appengine.py** — class: AppEngineManager, AppEnginePlatformError, AppEnginePlatformWarning; 17 imports; method: AppEngineManager.__enter__, AppEngineManager.__exit__, AppEngineManager.__init__, AppEngineManager._get_absolute_timeout, AppEngineManager._get_retries, AppEngineManager._urlfetch_response_to_http_response; module: appengine
**ntlmpool.py** — class: NTLMConnectionPool; 6 imports; method: NTLMConnectionPool.__init__, NTLMConnectionPool._new_conn, NTLMConnectionPool.urlopen; module: ntlmpool
**pyopenssl.py** — class: PyOpenSSLContext, WrappedSocket; function: _dnsname_to_stdlib, _validate_dependencies_met, _verify_callback, extract_from_urllib3, get_subj_alt_name, inject_into_urllib3; 21 imports; method: PyOpenSSLContext.__init__, PyOpenSSLContext.load_cert_chain, PyOpenSSLContext.load_verify_locations, PyOpenSSLContext.options, PyOpenSSLContext.set_alpn_protocols, PyOpenSSLContext.set_ciphers; module: pyopenssl
**securetransport.py** — class: SecureTransportContext, WrappedSocket; function: _read_callback, _write_callback, extract_from_urllib3, inject_into_urllib3; 25 imports; method: SecureTransportContext.__init__, SecureTransportContext.check_hostname, SecureTransportContext.load_cert_chain, SecureTransportContext.load_default_certs, SecureTransportContext.load_verify_locations, SecureTransportContext.options; module: securetransport; rationale: [TODO] Update in line with above., [TODO] Well, crap., [TODO] should I do clean shutdown here? Do I have to?
**socks.py** — class: SOCKSConnection, SOCKSHTTPConnectionPool, SOCKSHTTPSConnection, SOCKSHTTPSConnectionPool, SOCKSProxyManager; 15 imports; method: SOCKSConnection.__init__, SOCKSConnection._new_conn, SOCKSProxyManager.__init__; module: socks
**exceptions.py** — class: BodyNotHttplibCompatible, ClosedPoolError, ConnectTimeoutError, DecodeError, DependencyWarning, EmptyPoolError; 2 imports; method: HeaderParsingError.__init__, HostChangedError.__init__, IncompleteRead.__init__, IncompleteRead.__repr__, InvalidChunkLength.__init__, InvalidChunkLength.__repr__; module: exceptions
**fields.py** — class: RequestField; function: _replace_multiple, format_header_param_html5, format_header_param_rfc2231, guess_content_type; 5 imports; method: RequestField.__init__, RequestField._render_part, RequestField._render_parts, RequestField.from_tuples, RequestField.make_multipart, RequestField.render_headers; module: fields
**filepost.py** — function: choose_boundary, encode_multipart_formdata, iter_field_objects, iter_fields; 8 imports; module: filepost
**makefile.py** — function: backport_makefile; 2 imports; module: makefile
**weakref_finalize.py** — class: weakref_finalize; 6 imports; method: weakref_finalize.__call__, weakref_finalize.__init__, weakref_finalize.__repr__, weakref_finalize._exitfunc, weakref_finalize._select_for_exit, weakref_finalize.alive; module: weakref_finalize
**six.py** — class: Module_six_moves_urllib, Module_six_moves_urllib_error, Module_six_moves_urllib_parse, Module_six_moves_urllib_request, Module_six_moves_urllib_response, Module_six_moves_urllib_robotparser; function: _add_doc, _import_module, add_metaclass, add_move, assertCountEqual, assertNotRegex; 10 imports; method: Module_six_moves_urllib.__dir__, MovedAttribute.__init__, MovedAttribute._resolve, MovedModule.__getattr__, MovedModule.__init__, MovedModule._resolve; module: six
**poolmanager.py** — class: PoolManager, ProxyManager; function: _default_key_normalizer, proxy_from_url; 19 imports; method: PoolManager.__enter__, PoolManager.__exit__, PoolManager.__init__, PoolManager._merge_pool_kwargs, PoolManager._new_pool, PoolManager._proxy_requires_url_absolute_form; module: poolmanager
**request.py** — class: RequestMethods; 5 imports; method: RequestMethods.__init__, RequestMethods.request, RequestMethods.request_encode_body, RequestMethods.request_encode_url, RequestMethods.urlopen; module: request
**response.py** — class: DeflateDecoder, GzipDecoder, GzipDecoderState, HTTPResponse, MultiDecoder; function: _get_decoder; 26 imports; method: DeflateDecoder.__getattr__, DeflateDecoder.__init__, DeflateDecoder.decompress, GzipDecoder.__getattr__, GzipDecoder.__init__, GzipDecoder.decompress; module: response; rationale: [FIXME] Ideally we'd like to include the url in the ReadTimeoutError but, [FIXME] Is there a better way to differentiate between SSLErrors?, [FIXME] Rewrite this method and make it a class with a better structured logic., [NOTE] content-encoding value should be case-insensitive, per RFC 7230
**__init__.py** — 25 imports; module: __init__
**connection.py** — function: _has_ipv6, _set_socket_options, allowed_gai_family, create_connection, is_connection_dropped; 7 imports; module: connection
**proxy.py** — function: connection_requires_http_tunnel, create_proxy_ssl_context; 3 imports; module: proxy
**queue.py** — class: LifoQueue; 4 imports; method: LifoQueue._get, LifoQueue._init, LifoQueue._put, LifoQueue._qsize; module: queue
**request.py** — function: make_headers, rewind_body, set_file_position; 5 imports; module: request
**response.py** — function: assert_header_parsing, is_fp_closed, is_response_to_head; 5 imports; module: response; rationale: [FIXME] Can we do this somehow without accessing private httplib _method?
**retry.py** — class: Retry, _RetryMeta; 16 imports; method: Retry.__getattr__, Retry.__init__, Retry.__repr__, Retry._is_connection_error, Retry._is_method_retryable, Retry._is_read_error; module: retry; rationale: [TODO] Deprecated, remove in v2.0, [TODO] For now favor if the Retry implementation sets its own method_whitelist, [TODO] If already given in **kw we use what's given to us, [TODO] In v2 we can remove this sentinel and metaclass with deprecated options., [TODO] Remove this deprecated alias in v2.0
**ssl_.py** — function: _const_compare_digest_backport, _is_key_file_encrypted, _ssl_wrap_socket_impl, assert_fingerprint, create_urllib3_context, is_ipaddress; 30 imports; module: ssl_; rationale: [NOTE] This branch of code and all the variables in it are no longer
**ssl_match_hostname.py** — class: CertificateError; function: _dnsname_match, _ipaddress_match, _to_unicode, match_hostname; 3 imports; module: ssl_match_hostname; rationale: [NOTE] This file is under the PSF license as the code comes from the python
**ssltransport.py** — class: SSLTransport; 5 imports; method: SSLTransport.__enter__, SSLTransport.__exit__, SSLTransport.__init__, SSLTransport._decref_socketios, SSLTransport._ssl_io_loop, SSLTransport._validate_ssl_context_for_tls_in_tls; module: ssltransport
**timeout.py** — class: Timeout; 5 imports; method: Timeout.__init__, Timeout.__repr__, Timeout._validate_timeout, Timeout.clone, Timeout.connect_timeout, Timeout.from_float; module: timeout
**url.py** — class: Url; function: _encode_invalid_chars, _encode_target, _idna_encode, _normalize_host, _remove_path_dot_segments, get_host; 6 imports; method: Url.__new__, Url.__str__, Url.hostname, Url.netloc, Url.request_uri, Url.url; module: url; rationale: [TODO] Remove this when we break backwards compatibility.
**wait.py** — class: NoWayToWaitForSocketError; function: _have_working_poll, null_wait_for_socket, poll_wait_for_socket, select_wait_for_socket, wait_for_read, wait_for_socket; 6 imports; module: wait
**__init__.py** — class: Encoding, IncrementalDecoder, IncrementalEncoder; function: _detect_bom, _get_encoding, _iter_decode_generator, _iter_encode_generator, ascii_lower, decode; 4 imports; method: Encoding.__init__, Encoding.__repr__, IncrementalDecoder.__init__, IncrementalDecoder.decode, IncrementalEncoder.__init__; module: __init__
**labels.py** — module: labels
**mklabels.py** — function: assert_lower, generate; 3 imports; module: mklabels
**tests.py** — function: assert_raises, test_all_labels, test_decode, test_encode, test_invalid_label, test_iter_decode; 10 imports; module: tests
**x_user_defined.py** — class: Codec, IncrementalDecoder, IncrementalEncoder, StreamReader, StreamWriter; 2 imports; method: Codec.decode, Codec.encode, IncrementalDecoder.decode, IncrementalEncoder.encode; module: x_user_defined
**__init__.py** — class: ContextualVersionConflict, DefaultProvider, DistInfoDistribution, Distribution, DistributionNotFound, EggInfoDistribution; function: __getstate__, __setstate__, _always_object, _by_version_descending, _bypass_ensure_directory, _call_aside; 44 imports; method: ContextualVersionConflict.required_by, DefaultProvider._get, DefaultProvider._has, DefaultProvider._isdir, DefaultProvider._listdir, DefaultProvider._register; module: __init__; rationale: [FIXME] 'Distribution.insert_on' is too complex (13), [FIXME] 'WorkingSet.resolve' is too complex (11), [FIXME] 'ZipProvider._extract_resource' is too complex (12)
**appdirs.py** — class: AppDirs; function: _get_win_folder_from_registry, _get_win_folder_with_ctypes, _get_win_folder_with_jna, _get_win_folder_with_pywin32, site_config_dir, site_data_dir; 14 imports; method: AppDirs.__init__, AppDirs.site_config_dir, AppDirs.site_data_dir, AppDirs.user_cache_dir, AppDirs.user_config_dir, AppDirs.user_data_dir; module: appdirs
**__init__.py** — 12 imports; module: __init__
**_adapters.py** — class: CompatibilityFiles, SpecLoaderAdapter, TraversableResourcesLoader; function: _io_wrapper, wrap_spec; 3 imports; method: CompatibilityFiles.__getattr__, CompatibilityFiles.__init__, CompatibilityFiles._native, CompatibilityFiles._reader, CompatibilityFiles.files, SpecLoaderAdapter.__getattr__; module: _adapters
**_common.py** — function: _, _tempfile, as_file, files, from_package, get_package; 12 imports; module: _common
**_compat.py** — class: TraversableResourcesLoader; function: wrap_spec; 10 imports; method: TraversableResourcesLoader.__init__, TraversableResourcesLoader.get_resource_reader, TraversableResourcesLoader.path; module: _compat
**_itertools.py** — function: unique_everseen; 8 imports; module: _itertools
**_legacy.py** — function: contents, deprecated, is_resource, normalize_path, open_binary, open_text; 12 imports; module: _legacy
**abc.py** — class: ResourceReader, Traversable, TraversableResources; 6 imports; method: ResourceReader.contents, ResourceReader.is_resource, ResourceReader.open_resource, ResourceReader.resource_path, Traversable.__truediv__, Traversable.is_dir; module: abc
**readers.py** — class: FileReader, MultiplexedPath, NamespaceReader, ZipReader; function: remove_duplicates; 6 imports; method: FileReader.__init__, FileReader.files, FileReader.resource_path, MultiplexedPath.__init__, MultiplexedPath.__repr__, MultiplexedPath.is_dir; module: readers
**simple.py** — class: ResourceContainer, ResourceHandle, SimpleReader, TraversableReader; 7 imports; method: ResourceContainer.__init__, ResourceContainer.is_dir, ResourceContainer.is_file, ResourceContainer.iterdir, ResourceContainer.joinpath, ResourceContainer.open; module: simple
**context.py** — class: ExceptionTrap, suppress; function: infer_compression, null, pushd, repo_context, tarball_context, temp_dir; 7 imports; method: ExceptionTrap.__bool__, ExceptionTrap.__enter__, ExceptionTrap.__exit__, ExceptionTrap.__init__, ExceptionTrap.passes, ExceptionTrap.raises; module: context
**functools.py** — class: Throttler; function: _special_method_cache, apply, assign_params, call_aside, compose, except_; 9 imports; method: Throttler.__call__, Throttler.__get__, Throttler.__init__, Throttler._wait, Throttler.reset; module: functools
**__init__.py** — class: FoldedCase, SeparatedValues, Splitter, Stripper, WordSet; function: _, _nonblank, drop_comment, indent, is_binary, is_decodable; 9 imports; method: FoldedCase.__contains__, FoldedCase.__eq__, FoldedCase.__gt__, FoldedCase.__hash__, FoldedCase.__lt__, FoldedCase.__ne__; module: __init__
**__init__.py** — 2 imports; module: __init__
**more.py** — class: AbortThread, SequenceView, UnequalIterablesError, bucket, callback_iter, countable; function: _chunked_even_finite, _chunked_even_online, _islice_helper, _sample_unweighted, _sample_weighted, _zip_equal; 50 imports; method: SequenceView.__getitem__, SequenceView.__init__, SequenceView.__len__, SequenceView.__repr__, UnequalIterablesError.__init__, bucket.__contains__; module: more
**recipes.py** — function: _pairwise, all_equal, before_and_after, consume, convolve, dotproduct; 17 imports; module: recipes
**__about__.py** — module: __about__
**__init__.py** — 8 imports; module: __init__
**_manylinux.py** — class: _ELFFileHeader, _GLibCVersion; function: _get_elf_header, _get_glibc_version, _glibc_version_string, _glibc_version_string_confstr, _glibc_version_string_ctypes, _have_compatible_abi; 15 imports; method: _ELFFileHeader.__init__; module: _manylinux
**_musllinux.py** — class: _MuslVersion; function: _get_musl_version, _parse_ld_musl_from_elf, _parse_musl_version, _read_unpacked, platform_tags; 14 imports; module: _musllinux
**_structures.py** — class: InfinityType, NegativeInfinityType; method: InfinityType.__eq__, InfinityType.__ge__, InfinityType.__gt__, InfinityType.__hash__, InfinityType.__le__, InfinityType.__lt__; module: _structures
**markers.py** — class: InvalidMarker, Marker, Node, Op, Undefined, UndefinedComparison; function: _coerce_parse_result, _eval_op, _evaluate_markers, _format_marker, _get_env, default_environment; 22 imports; method: Marker.__init__, Marker.__repr__, Marker.__str__, Marker.evaluate, Node.__init__, Node.__repr__; module: markers
**requirements.py** — class: InvalidRequirement, Requirement; 21 imports; method: Requirement.__init__, Requirement.__repr__, Requirement.__str__; module: requirements; rationale: [TODO] Can we normalize the name and extra name?, [TODO] Can we test whether something is contained within a requirement?
**specifiers.py** — class: BaseSpecifier, InvalidSpecifier, LegacySpecifier, Specifier, SpecifierSet, _IndividualSpecifier; function: _is_not_suffix, _pad_version, _require_version_compare, _version_split; 20 imports; method: BaseSpecifier.__eq__, BaseSpecifier.__hash__, BaseSpecifier.__str__, BaseSpecifier.contains, BaseSpecifier.filter, BaseSpecifier.prereleases; module: specifiers; rationale: [NOTE] This means that 1.0.dev1 would not be contained in something, [NOTE] This use of all() here means that an empty set of specifiers
**tags.py** — class: Tag; function: _abi3_applies, _cpython_abis, _generic_abi, _generic_platforms, _get_config_var, _linux_platforms; 17 imports; method: Tag.__eq__, Tag.__hash__, Tag.__init__, Tag.__repr__, Tag.__str__, Tag.abi; module: tags; rationale: [TODO] Need to care about 32-bit PPC for ppc64 through 10.2?
**utils.py** — class: InvalidSdistFilename, InvalidWheelFilename; function: canonicalize_name, canonicalize_version, parse_sdist_filename, parse_wheel_filename; 10 imports; module: utils
**version.py** — class: InvalidVersion, LegacyVersion, Version, _BaseVersion; function: _cmpkey, _legacy_cmpkey, _parse_letter_version, _parse_local_version, _parse_version_parts, parse; 15 imports; method: LegacyVersion.__init__, LegacyVersion.__repr__, LegacyVersion.__str__, LegacyVersion.base_version, LegacyVersion.dev, LegacyVersion.epoch; module: version
**__init__.py** — class: version_info; 17 imports; method: version_info.__repr__, version_info.__str__, version_info.__version__; module: __init__
**actions.py** — class: OnlyOnce; function: match_only_at_col, remove_quotes, replace_with, with_attribute, with_class; 3 imports; method: OnlyOnce.__call__, OnlyOnce.__init__, OnlyOnce.reset; module: actions
**common.py** — class: pyparsing_common; 5 imports; method: pyparsing_common.convert_to_date, pyparsing_common.convert_to_datetime, pyparsing_common.strip_html_tags; module: common
**core.py** — class: And, AtLineStart, AtStringStart, CaselessKeyword, CaselessLiteral, Char; function: _default_exception_debug_action, _default_start_debug_action, _default_success_debug_action, _should_enable_warnings, _trim_arity, autoname_elements; 46 imports; method: And.__iadd__, And.__init__, And._checkRecursion, And._generateDefaultName, And.parseImpl, And.streamline; module: core
**__init__.py** — class: AnnotatedItem, ConverterState, EachItem, EditablePartial, ElementState; function: _apply_diagram_item_enhancements, _should_vertical, _to_diagram_element, _visible_exprs, _worth_extracting, railroad_to_html; 14 imports; method: AnnotatedItem.__init__, ConverterState.__contains__, ConverterState.__delitem__, ConverterState.__getitem__, ConverterState.__init__, ConverterState.__setitem__; module: __init__; rationale: [NOTE] ideally this would be a dataclass, but we're supporting Python 3.5+ so we can't , [NOTE] this should be a dataclass, but we have to support Python 3.5
**exceptions.py** — class: ExceptionWordUnicode, ParseBaseException, ParseException, ParseFatalException, ParseSyntaxException, RecursiveGrammarException; 10 imports; method: ParseBaseException.__init__, ParseBaseException.__repr__, ParseBaseException.__str__, ParseBaseException._from_exception, ParseBaseException.col, ParseBaseException.column; module: exceptions
**helpers.py** — class: OpAssoc; function: _makeTags, counted_array, delimited_list, dict_of, indentedBlock, infix_notation; 8 imports; module: helpers
**results.py** — class: ParseResults, _ParseResultsWithOffset; 8 imports; method: ParseResults.__add__, ParseResults.__bool__, ParseResults.__contains__, ParseResults.__delitem__, ParseResults.__dir__, ParseResults.__getattr__; module: results
**testing.py** — class: pyparsing_test; 7 imports; method: pyparsing_test.with_line_numbers; module: testing
**unicode.py** — class: _lazyclassproperty, pyparsing_unicode, unicode_set; 5 imports; method: _lazyclassproperty.__get__, _lazyclassproperty.__init__, unicode_set._chars_for_ranges, unicode_set.alphanums, unicode_set.alphas, unicode_set.identbodychars; module: unicode
**util.py** — class: LRUMemo, UnboundedMemo, _FifoCache, _UnboundedCache, __config_flags; function: _collapse_string_to_ranges, _escape_regex_range_chars, _flatten, col, line, lineno; 8 imports; method: LRUMemo.__delitem__, LRUMemo.__getitem__, LRUMemo.__init__, LRUMemo.__setitem__, LRUMemo.clear, UnboundedMemo.__delitem__; module: util
**zipp.py** — class: CompleteDirs, FastLookup, Path; function: _ancestry, _difference, _parents, _pathlib_compat; 8 imports; method: CompleteDirs._implied_dirs, CompleteDirs._name_set, CompleteDirs.make, CompleteDirs.namelist, CompleteDirs.resolve_dir, FastLookup._name_set; module: zipp
**__init__.py** — class: VendorImporter; 2 imports; method: VendorImporter.__init__, VendorImporter._module_matches_namespace, VendorImporter.create_module, VendorImporter.exec_module, VendorImporter.find_spec, VendorImporter.install; module: __init__
**__init__.py** — function: parse_file, preprocess_file; 3 imports; module: __init__
**_ast_gen.py** — class: ASTCodeGenerator, NodeCfg; 3 imports; method: ASTCodeGenerator.__init__, ASTCodeGenerator.generate, ASTCodeGenerator.parse_cfgfile, NodeCfg.__init__, NodeCfg._gen_attr_names, NodeCfg._gen_children; module: _ast_gen
**ast_transforms.py** — function: _extract_nested_case, _fix_atomic_specifiers_once, fix_atomic_specifiers, fix_switch_cases; 5 imports; module: ast_transforms
**c_ast.py** — class: Alignas, ArrayDecl, ArrayRef, Assignment, BinaryOp, Break; function: _repr; 5 imports; method: Alignas.__init__, Alignas.__iter__, Alignas.children, ArrayDecl.__init__, ArrayDecl.__iter__, ArrayDecl.children; module: c_ast
**c_generator.py** — class: CGenerator; 4 imports; method: CGenerator.__init__, CGenerator._generate_decl, CGenerator._generate_enum_body, CGenerator._generate_stmt, CGenerator._generate_struct_union_body, CGenerator._generate_struct_union_enum; module: c_generator; rationale: [NOTE] all binary operators are left-to-right associative
**c_lexer.py** — class: CLexer, _FixedToken, _RegexAction, _RegexRule, _Token; 8 imports; method: CLexer.__init__, CLexer._error, CLexer._handle_ppline, CLexer._handle_pppragma, CLexer._init_state, CLexer._make_token; module: c_lexer; rationale: [NOTE] a-zA-Z and '.-~^_!=&;,' are allowed as escape chars to support #line
**c_parser.py** — class: CParser, Coord, ParseError, _DeclInfo, _DeclSpec, _TokenStream; 15 imports; method: CParser.__init__, CParser._accept, CParser._add_declaration_specifier, CParser._add_identifier, CParser._add_typedef_name, CParser._advance; module: c_parser
**__init__.py** — function: __dir__, __getattr__; 60 imports; module: __init__
**_config.py** — class: ConfigWrapper, ConfigWrapperStack; function: check_deprecated, prepare_config; 23 imports; method: ConfigWrapper.__init__, ConfigWrapper.__repr__, ConfigWrapper.core_config, ConfigWrapper.for_model, ConfigWrapperStack.__init__, ConfigWrapperStack.push; module: _config
**_core_metadata.py** — class: CoreMetadata; function: update_core_metadata; 10 imports; module: _core_metadata
**_core_utils.py** — function: _clean_schema_for_pretty_print, get_ref, get_type_ref, is_core_schema, is_core_schema_field, is_function_with_inner_schema; 20 imports; module: _core_utils
**_dataclasses.py** — function: as_dataclass_field, complete_dataclass, is_stdlib_dataclass, patch_base_fields, set_dataclass_fields; 36 imports; module: _dataclasses
**_decorators.py** — class: Decorator, DecoratorInfos, FieldSerializerDecoratorInfo, FieldValidatorDecoratorInfo, ModelSerializerDecoratorInfo, ModelValidatorDecoratorInfo; function: _decorator_infos_for_class, _is_classmethod_from_sig, _serializer_info_arg, count_positional_required_params, ensure_classmethod_based_on_signature, ensure_property; 40 imports; method: Decorator.bind_to_cls, Decorator.build, DecoratorInfos._validate, DecoratorInfos.build, DecoratorInfos.update_from_config, PydanticDescriptorProxy.__get__; module: _decorators
**_decorators_v1.py** — class: V1OnlyValueValidator, V1RootValidatorFunction, V1ValidatorWithKwargs, V1ValidatorWithValues, V1ValidatorWithValuesAndKwargs, V1ValidatorWithValuesKwOnly; function: can_be_keyword, make_generic_v1_field_validator, make_v1_generic_root_validator; 10 imports; method: V1OnlyValueValidator.__call__, V1RootValidatorFunction.__call__, V1ValidatorWithKwargs.__call__, V1ValidatorWithValues.__call__, V1ValidatorWithValuesAndKwargs.__call__, V1ValidatorWithValuesKwOnly.__call__; module: _decorators_v1
**_discriminated_union.py** — class: MissingDefinitionForUnionRef, _ApplyInferredDiscriminator; function: apply_discriminator, set_discriminator_in_metadata; 13 imports; method: MissingDefinitionForUnionRef.__init__, _ApplyInferredDiscriminator.__init__, _ApplyInferredDiscriminator._apply_to_root, _ApplyInferredDiscriminator._handle_choice, _ApplyInferredDiscriminator._infer_discriminator_values_for_choice, _ApplyInferredDiscriminator._infer_discriminator_values_for_dataclass_choice; module: _discriminated_union; rationale: [NOTE] following the v1 implementation, we currently disallow the use of different alia
**_docs_extraction.py** — class: DocstringVisitor; function: _dedent_source_lines, _extract_source_from_frame, extract_docstrings_from_cls; 6 imports; method: DocstringVisitor.__init__, DocstringVisitor.visit, DocstringVisitor.visit_AnnAssign, DocstringVisitor.visit_Expr; module: _docs_extraction
**_fields.py** — class: PydanticExtraInfo, PydanticMetadata; function: _apply_alias_generator_to_field_info, _apply_field_title_generator_to_field_info, _check_protected_namespaces, _general_metadata_cls, _recreate_field_info, _update_fields_from_docstrings; 37 imports; module: _fields; rationale: [NOTE] we may need to change this logic if/when we introduce a `BareModel` class with n, [TODO] We should probably do something with this so that validate_assignment behaves pr, [TODO] make kw_only when we drop support for 3.9., [TODO] make use of PEP 747:, [TODO] same note as above re validate_assignment
**_forward_ref.py** — class: PydanticRecursiveRef; 3 imports; method: PydanticRecursiveRef.__call__, PydanticRecursiveRef.__or__, PydanticRecursiveRef.__ror__; module: _forward_ref
**_generate_schema.py** — class: GenerateSchema, InvalidSchemaError, _Definitions, _FieldNameStack, _ModelTypeStack; function: _add_custom_serialization_from_json_encoders, _convert_to_aliases, _extract_get_pydantic_json_schema, _extract_json_schema_info_from_field_info, _inlining_behavior, _validators_require_validate_default; 152 imports; method: GenerateSchema.__init__, GenerateSchema.__init_subclass__, GenerateSchema._add_js_function, GenerateSchema._annotated_schema, GenerateSchema._apply_annotations, GenerateSchema._apply_discriminator_to_union; module: _generate_schema; rationale: [HACK] we don't want to emit the warning for `FieldInfo` subclasses, because FastAPI do, [NOTE] This conditional can be removed when we drop support for Python 3.10., [NOTE] This does not play very well with type checkers. For example,, [NOTE] if schema is of type `'definition-ref'`, we might want to copy it as a, [NOTE] subtle difference: `tuple[()]` gives `params=()`, whereas `typing.Tuple[()]` giv, [NOTE] this logic doesn't play well when core schemas with deferred discriminator metad
**_generics.py** — class: LimitedDict, PydanticGenericMetadata; function: _early_cache_key, _get_caller_frame_info, _late_cache_key, _union_orderings_key, create_generic_submodel, generic_recursion_self_type; 29 imports; method: LimitedDict.__init__, LimitedDict.__setitem__; module: _generics; rationale: [NOTE] We want to remove LimitedDict, but to do this, we'd need to improve the handling, [TODO] This could be unified with `get_standard_typevars_map` if we stored the generic 
**_git.py** — function: git_revision, have_git, is_git_repo; 3 imports; module: _git
**_import_utils.py** — function: import_cached_base_model, import_cached_field_info; 4 imports; module: _import_utils
**_internal_dataclass.py** — 1 imports; module: _internal_dataclass
**_known_annotated_metadata.py** — function: _get_at_to_constraint_map, apply_known_metadata, as_jsonable_value, check_metadata, collect_known_metadata, expand_grouped_metadata; 18 imports; module: _known_annotated_metadata; rationale: [NOTE] B023 is ignored because even though we iterate over `other_metadata`, it is guar, [TODO] this is a bit redundant, we could probably avoid some of these
**_mock_val_ser.py** — class: MockCoreSchema, MockValSer; function: set_dataclass_mocks, set_model_mocks, set_type_adapter_mocks; 20 imports; method: MockCoreSchema.__getitem__, MockCoreSchema.__init__, MockCoreSchema.__iter__, MockCoreSchema.__len__, MockCoreSchema._get_built, MockCoreSchema.rebuild; module: _mock_val_ser
**_model_construction.py** — class: ModelMetaclass, _DeprecatedFieldDescriptor, _ModelNamespaceDict, _PydanticWeakRef; function: NoInitField, build_lenient_weakvaluedict, complete_model_class, default_ignored_types, get_model_post_init, init_private_attributes; 67 imports; method: ModelMetaclass.__dir__, ModelMetaclass.__fields__, ModelMetaclass.__new__, ModelMetaclass.__prepare__, ModelMetaclass.__pydantic_fields_complete__, ModelMetaclass._collect_bases_data; module: _model_construction; rationale: [NOTE] when coming from `ModelMetaclass.__new__()`, this results in fields being built 
**_namespace_utils.py** — class: LazyLocalNamespace, NamespacesTuple, NsResolver; function: get_module_ns_of, ns_for_function; 15 imports; method: LazyLocalNamespace.__contains__, LazyLocalNamespace.__getitem__, LazyLocalNamespace.__init__, LazyLocalNamespace.__iter__, LazyLocalNamespace.__len__, LazyLocalNamespace.data; module: _namespace_utils; rationale: [TODO] should we merge the parent namespace here?
**_repr.py** — class: PlainRepr, Representation; function: display_as_type; 15 imports; method: PlainRepr.__repr__, Representation.__pretty__, Representation.__repr__, Representation.__repr_args__, Representation.__repr_name__, Representation.__repr_recursion__; module: _repr
**_schema_gather.py** — class: GatherContext, GatherResult, MissingDefinitionError; function: gather_schemas_for_cleaning, traverse_definition_ref, traverse_metadata, traverse_schema; 10 imports; method: MissingDefinitionError.__init__; module: _schema_gather
**_schema_generation_shared.py** — class: CallbackGetCoreSchemaHandler, GenerateJsonSchemaHandler; 13 imports; method: CallbackGetCoreSchemaHandler.__call__, CallbackGetCoreSchemaHandler.__init__, CallbackGetCoreSchemaHandler._get_types_namespace, CallbackGetCoreSchemaHandler.field_name, CallbackGetCoreSchemaHandler.generate_schema, CallbackGetCoreSchemaHandler.resolve_ref_schema; module: _schema_generation_shared
**_serializers.py** — function: serialize_sequence_via_list; 7 imports; module: _serializers
**_signature.py** — class: _HAS_DEFAULT_FACTORY_CLASS; function: _field_name_for_signature, _generate_signature_parameters, _process_param_defaults, generate_pydantic_signature; 13 imports; method: _HAS_DEFAULT_FACTORY_CLASS.__repr__; module: _signature
**_typing_extra.py** — function: _eval_type, _eval_type_backport, _type_convert, annotated_type, eval_type, eval_type_backport; 32 imports; module: _typing_extra; rationale: [TODO] Ideally, we should avoid relying on the private `typing` constructs:
**_utils.py** — class: SafeGetItemProxy, ValueItems, deprecated_instance_property; function: all_identical, can_be_positional, deep_update, get_first_not_none, is_model_class, is_valid_identifier; 38 imports; method: SafeGetItemProxy.__getitem__, ValueItems.__init__, ValueItems.__repr_args__, ValueItems._coerce_items, ValueItems._coerce_value, ValueItems._normalize_indexes; module: _utils; rationale: [NOTE] fget should be a classmethod:, [NOTE] including ModuleType will differ from behaviour of deepcopy by not producing err
**_validate_call.py** — class: ValidateCallWrapper; function: extract_function_name, extract_function_qualname, update_wrapper_attributes; 17 imports; method: ValidateCallWrapper.__call__, ValidateCallWrapper.__init__, ValidateCallWrapper._create_validators; module: _validate_call
**_validators.py** — function: _extract_decimal_digits_info, _import_string_logic, _safe_repr, compile_pattern, decimal_places_validator, defaultdict_validator; 31 imports; module: _validators; rationale: [TODO] refactor sequence validation to validate with either a list or a tuple
**_migration.py** — function: getattr_migration; 8 imports; module: _migration
**alias_generators.py** — function: to_camel, to_pascal, to_snake; 1 imports; module: alias_generators; rationale: [TODO] in V3, change the argument names to be more descriptive
**aliases.py** — class: AliasChoices, AliasGenerator, AliasPath; 7 imports; method: AliasChoices.__init__, AliasChoices.convert_to_aliases, AliasGenerator._generate_alias, AliasGenerator.generate_aliases, AliasPath.__init__, AliasPath.convert_to_aliases; module: aliases
**annotated_handlers.py** — class: GetCoreSchemaHandler, GetJsonSchemaHandler; 8 imports; method: GetCoreSchemaHandler.__call__, GetCoreSchemaHandler._get_types_namespace, GetCoreSchemaHandler.field_name, GetCoreSchemaHandler.generate_schema, GetCoreSchemaHandler.resolve_ref_schema, GetJsonSchemaHandler.__call__; module: annotated_handlers
**class_validators.py** — 1 imports; module: class_validators
**color.py** — class: Color, RGBA; function: float_to_255, ints_to_rgba, parse_color_value, parse_float_alpha, parse_hsl, parse_str; 17 imports; method: Color.__eq__, Color.__get_pydantic_core_schema__, Color.__get_pydantic_json_schema__, Color.__hash__, Color.__init__, Color.__repr_args__; module: color
**config.py** — class: ConfigDict; function: with_config; 23 imports; module: config
**dataclasses.py** — function: _pydantic_fields_complete, dataclass, is_pydantic_dataclass, rebuild_dataclass; 31 imports; module: dataclasses
**datetime_parse.py** — 1 imports; module: datetime_parse
**decorator.py** — 1 imports; module: decorator
**class_validators.py** — function: root_validator, validator; 19 imports; module: class_validators
**config.py** — class: BaseConfig, Extra, _ConfigMetaclass, _ExtraMeta; 8 imports; method: BaseConfig.__getattr__, BaseConfig.__init_subclass__, _ConfigMetaclass.__getattr__, _ExtraMeta.__getattribute__; module: config
**copy_internals.py** — function: _calculate_keys, _copy_and_set_values, _get_value, _iter; 12 imports; module: copy_internals
**decorator.py** — class: ValidatedFunction; function: validate_arguments; 21 imports; method: ValidatedFunction.__init__, ValidatedFunction.build_values, ValidatedFunction.call, ValidatedFunction.create_model, ValidatedFunction.execute, ValidatedFunction.init_model_instance; module: decorator
**json.py** — function: custom_pydantic_encoder, decimal_encoder, isoformat, pydantic_encoder, timedelta_isoformat; 28 imports; module: json; rationale: [TODO] Add a suggested migration path once there is a way to use custom encoders
**parse.py** — class: Protocol; function: load_file, load_str_bytes; 11 imports; module: parse
**tools.py** — function: parse_obj_as, schema_json_of, schema_of; 13 imports; module: tools
**env_settings.py** — 1 imports; module: env_settings
**error_wrappers.py** — 1 imports; module: error_wrappers
**errors.py** — class: PydanticErrorMixin, PydanticForbiddenQualifier, PydanticImportError, PydanticInvalidForJsonSchema, PydanticSchemaGenerationError, PydanticUndefinedAnnotation; 10 imports; method: PydanticErrorMixin.__init__, PydanticErrorMixin.__str__, PydanticForbiddenQualifier.__init__, PydanticImportError.__init__, PydanticInvalidForJsonSchema.__init__, PydanticSchemaGenerationError.__init__; module: errors
**__init__.py** — module: __init__
**arguments_schema.py** — function: generate_arguments_schema; 9 imports; module: arguments_schema
**missing_sentinel.py** — 1 imports; module: missing_sentinel
**pipeline.py** — class: _Constraint, _Eq, _FieldTypeMarker, _In, _NotEq, _NotIn; function: _apply_constraint, _apply_parse, _apply_step, _apply_transform, _check_func; 28 imports; method: _Pipeline.__get_pydantic_core_schema__, _Pipeline.__supports_type__, _Pipeline.constrain, _Pipeline.datetime_tz, _Pipeline.datetime_tz_aware, _Pipeline.datetime_tz_naive; module: pipeline; rationale: [TODO] ultimately, make this public, see https://github.com/pydantic/pydantic/pull/9459, [TODO] use `_typing_extra.EllipsisType` when we drop Py3.9
**fields.py** — class: ComputedFieldInfo, FieldInfo, ModelPrivateAttr, _EmptyKwargs, _FieldInfoAsDict, _FieldInfoInputs; function: Field, PrivateAttr, _wrapped_property_is_private, computed_field; 55 imports; method: ComputedFieldInfo.__copy__, ComputedFieldInfo._apply_alias_generator, ComputedFieldInfo._update_from_config, ComputedFieldInfo.deprecation_message, FieldInfo.__init__, FieldInfo.__repr_args__; module: fields; rationale: [HACK] It is common for users to define "make model partial" (or similar) utilities, th, [NOTE] Actual return type is 'FieldInfo', but we want to help type checkers, [NOTE] Actual return type is 'ModelPrivateAttr', but we want to help type checkers, [NOTE] if you add a new field, add it to the `__copy__()` implementation., [NOTE] in theory, the second `pop()` arguments are not required below, as defaults are , [NOTE] to get proper type checking on `exclude_if`'s argument, we could use `_T` instea
**functional_serializers.py** — class: PlainSerializer, WrapSerializer; function: field_serializer, model_serializer; 22 imports; method: PlainSerializer.__get_pydantic_core_schema__, WrapSerializer.__get_pydantic_core_schema__; module: functional_serializers
**functional_validators.py** — class: AfterValidator, BeforeValidator, FreeModelBeforeValidator, FreeModelBeforeValidatorWithoutInfo, ModelBeforeValidator, ModelBeforeValidatorWithoutInfo; function: field_validator, model_validator; 30 imports; method: AfterValidator.__get_pydantic_core_schema__, AfterValidator._from_decorator, BeforeValidator.__get_pydantic_core_schema__, BeforeValidator._from_decorator, FreeModelBeforeValidator.__call__, FreeModelBeforeValidatorWithoutInfo.__call__; module: functional_validators; rationale: [TODO] make use of PEP 747
**generics.py** — 1 imports; module: generics
**json.py** — 1 imports; module: json
**json_schema.py** — class: Examples, GenerateJsonSchema, PydanticJsonSchemaWarning, WithJsonSchema, _DefinitionsRemapping; function: _deduplicate_schemas, _get_all_json_refs, _get_ser_schema_for_default_value, _get_typed_dict_config, _make_json_hashable, model_json_schema; 63 imports; method: Examples.__get_pydantic_json_schema__, Examples.__hash__, Examples.__init__, GenerateJsonSchema.__init__, GenerateJsonSchema._build_definitions_remapping, GenerateJsonSchema._common_set_schema; module: json_schema; rationale: [NOTE] 'multi-host-uri' is a custom/pydantic-specific format, not part of the JSON Sche, [NOTE] This is for compatibility with V1; you can override if you want different behavi, [NOTE] this may not really be a JsonRef; we rely on having no collisions between JsonRe, [TODO] I dislike that we have to wrap these basic dict updates in callables, is there a, [TODO] Need to read the default value off of model config or whatever, [TODO] fixme - this is a workaround for the fact that we can't always resolve refs
**main.py** — class: BaseModel; function: _check_frozen, _model_field_setattr_handler, _private_setattr_handler, create_model; 73 imports; method: BaseModel.__class_getitem__, BaseModel.__copy__, BaseModel.__deepcopy__, BaseModel.__fields__, BaseModel.__fields_set__, BaseModel.__get_pydantic_core_schema__; module: main; rationale: [NOTE] Contrary to standard python class and instances, when the Model class has a defa, [NOTE] In reality, `bool` should be replaced by `Literal[True]` but mypy fails to corre, [NOTE] Keep this type alias in sync with the stub definition in `pydantic-core`:, [NOTE] Many of the below class vars are defined in the metaclass, but we define them he, [NOTE] We currently special case properties and `cached_property`, but we might need, [NOTE] self.__pydantic_private__ cannot be None if self.__private_attributes__ has item
**mypy.py** — class: ChangeExplicitTypeOfAny, ModelConfigData, PydanticModelClassVar, PydanticModelField, PydanticModelTransformer, PydanticPlugin; function: add_method, error_extra_fields_on_root_model, error_from_attributes, error_invalid_config_value, error_required_dynamic_aliases, error_unexpected_behavior; 73 imports; method: ChangeExplicitTypeOfAny.__init__, ChangeExplicitTypeOfAny.visit_any, ModelConfigData.__init__, ModelConfigData.get_values_dict, ModelConfigData.setdefault, ModelConfigData.update; module: mypy; rationale: [NOTE] we would like the plugin generated node to dominate, but we still, [TODO] Only do this if the first argument of the decorated function is `cls`, [TODO] We shouldn't be performing type operations during the main
**networks.py** — class: AmqpDsn, AnyHttpUrl, AnyUrl, AnyWebsocketUrl, ClickHouseDsn, CockroachDsn; function: _build_pretty_email_regex, _build_type_adapter, import_email_validator, validate_email; 33 imports; method: CockroachDsn.host, NameEmail.__eq__, NameEmail.__get_pydantic_core_schema__, NameEmail.__get_pydantic_json_schema__, NameEmail.__init__, NameEmail.__str__; module: networks; rationale: [NOTE] all single host urls inherit from `AnyUrl` to preserve compatibility with pre-v2
**parse.py** — 1 imports; module: parse
**__init__.py** — class: BaseValidateHandlerProtocol, PydanticPluginProtocol, SchemaTypePath, ValidateJsonHandlerProtocol, ValidatePythonHandlerProtocol, ValidateStringsHandlerProtocol; 11 imports; method: BaseValidateHandlerProtocol.on_error, BaseValidateHandlerProtocol.on_exception, BaseValidateHandlerProtocol.on_success, PydanticPluginProtocol.new_schema_validator, ValidateJsonHandlerProtocol.on_enter, ValidatePythonHandlerProtocol.on_enter; module: __init__
**_loader.py** — function: get_plugins; 8 imports; module: _loader
**_schema_validator.py** — class: PluggableSchemaValidator; function: build_wrapper, create_schema_validator, filter_handlers; 18 imports; method: PluggableSchemaValidator.__getattr__, PluggableSchemaValidator.__init__; module: _schema_validator
**root_model.py** — class: RootModel; 18 imports; method: RootModel.__copy__, RootModel.__deepcopy__, RootModel.__eq__, RootModel.__getstate__, RootModel.__init__, RootModel.__init_subclass__; module: root_model
**schema.py** — 1 imports; module: schema
**tools.py** — 1 imports; module: tools
**type_adapter.py** — class: TypeAdapter; function: _getattr_no_parents, _type_has_config; 40 imports; method: TypeAdapter.__init__, TypeAdapter.__repr__, TypeAdapter._defer_build, TypeAdapter._fetch_parent_frame, TypeAdapter._init_core_attrs, TypeAdapter._model_config; module: type_adapter; rationale: [TODO] we don't go through the rebuild logic here directly because we don't want
**types.py** — class: AllowInfNan, Base64Encoder, Base64UrlEncoder, ByteSize, Discriminator, EncodedBytes; function: _check_annotated_type, _get_type_name, _secret_display, _serialize_secret, _serialize_secret_field, conbytes; 51 imports; method: AllowInfNan.__hash__, Base64Encoder.decode, Base64Encoder.encode, Base64Encoder.get_json_format, Base64UrlEncoder.decode, Base64UrlEncoder.encode; module: types; rationale: [NOTE] this will not work!, [NOTE] we may want to consider adding a convenience staticmethod `def for_type(type_: A
**typing.py** — 1 imports; module: typing
**utils.py** — 1 imports; module: utils
**__init__.py** — 22 imports; module: __init__
**_hypothesis_plugin.py** — function: _registered, add_luhn_digit, resolve_conbytes, resolve_condate, resolve_condecimal, resolve_confloat; 18 imports; module: _hypothesis_plugin
**annotated_types.py** — function: create_model_from_namedtuple, create_model_from_typeddict; 13 imports; module: annotated_types
**class_validators.py** — class: Validator, ValidatorGroup; function: _generic_validator_basic, _generic_validator_cls, _prepare_validator, extract_root_validators, extract_validators, gather_all_validators; 29 imports; method: Validator.__init__, ValidatorGroup.__init__, ValidatorGroup.check_for_unused, ValidatorGroup.get_validators; module: class_validators
**color.py** — class: Color, RGBA; function: float_to_255, ints_to_rgba, parse_color_value, parse_float_alpha, parse_hsl, parse_str; 16 imports; method: Color.__eq__, Color.__get_validators__, Color.__hash__, Color.__init__, Color.__modify_schema__, Color.__repr_args__; module: color
**config.py** — class: BaseConfig, Extra; function: get_config, inherit_config, prepare_config; 21 imports; method: BaseConfig.get_field_info, BaseConfig.prepare_field; module: config
**dataclasses.py** — class: DataclassProxy; function: _add_pydantic_validation_attributes, _dataclass_validate_assignment_setattr, _dataclass_validate_values, _get_validators, _validate_dataclass, create_pydantic_model_from_dataclass; 35 imports; method: DataclassProxy.__call__, DataclassProxy.__copy__, DataclassProxy.__deepcopy__, DataclassProxy.__getattr__, DataclassProxy.__init__, DataclassProxy.__instancecheck__; module: dataclasses
**datetime_parse.py** — function: _parse_timezone, from_unix_seconds, get_numeric, parse_date, parse_datetime, parse_duration; 11 imports; module: datetime_parse
**decorator.py** — class: ValidatedFunction; function: validate_arguments; 23 imports; method: ValidatedFunction.__init__, ValidatedFunction.build_values, ValidatedFunction.call, ValidatedFunction.create_model, ValidatedFunction.execute, ValidatedFunction.init_model_instance; module: decorator
**env_settings.py** — class: BaseSettings, EnvSettingsSource, InitSettingsSource, SecretsSettingsSource, SettingsError; function: find_case_path, read_env_file; 28 imports; method: BaseSettings.__init__, BaseSettings._build_values, EnvSettingsSource.__call__, EnvSettingsSource.__init__, EnvSettingsSource.__repr__, EnvSettingsSource._read_env_files; module: env_settings
**error_wrappers.py** — class: ErrorWrapper, ValidationError; function: _display_error_loc, _display_error_type_and_ctx, _get_exc_type, display_errors, error_dict, flatten_errors; 17 imports; method: ErrorWrapper.__init__, ErrorWrapper.__repr_args__, ErrorWrapper.loc_tuple, ValidationError.__init__, ValidationError.__repr_args__, ValidationError.__str__; module: error_wrappers
**errors.py** — class: AnyStrMaxLengthError, AnyStrMinLengthError, ArbitraryTypeError, BoolError, BytesError, CallableError; function: cls_kwargs; 12 imports; method: AnyStrMaxLengthError.__init__, AnyStrMinLengthError.__init__, ArbitraryTypeError.__init__, DecimalMaxDigitsError.__init__, DecimalMaxPlacesError.__init__, DecimalWholeDigitsError.__init__; module: errors
**fields.py** — class: DeferredType, FieldInfo, ModelField, ModelPrivateAttr, UndefinedType; function: Field, PrivateAttr, is_finalvar_with_default_val; 77 imports; method: FieldInfo.__init__, FieldInfo.__repr_args__, FieldInfo._validate, FieldInfo.get_constraints, FieldInfo.update_from_config, ModelField.__init__; module: fields
**generics.py** — class: GenericModel; function: _prepare_model_fields, check_parameters_count, get_caller_frame_info, iter_contained_typevars, replace_types; 37 imports; method: GenericModel.__class_getitem__, GenericModel.__concrete_name__, GenericModel.__parameterized_bases__; module: generics
**json.py** — function: custom_pydantic_encoder, decimal_encoder, isoformat, pydantic_encoder, timedelta_isoformat; 26 imports; module: json
**main.py** — class: BaseModel, ModelMetaclass; function: create_model, generate_hash_function, validate_custom_root_type, validate_model; 94 imports; method: BaseModel.__eq__, BaseModel.__get_validators__, BaseModel.__getstate__, BaseModel.__init__, BaseModel.__iter__, BaseModel.__repr_args__; module: main
**mypy.py** — class: ModelConfigData, PydanticModelField, PydanticModelTransformer, PydanticPlugin, PydanticPluginConfig; function: add_method, error_default_and_default_factory_specified, error_from_orm, error_invalid_config_value, error_required_dynamic_aliases, error_unexpected_behavior; 74 imports; method: ModelConfigData.__init__, ModelConfigData.set_values_dict, ModelConfigData.setdefault, ModelConfigData.update, PydanticModelField.__init__, PydanticModelField.deserialize; module: mypy; rationale: [NOTE] we would like the plugin generated node to dominate, but we still
**networks.py** — class: AmqpDsn, AnyHttpUrl, AnyUrl, CockroachDsn, EmailStr, FileUrl; function: ascii_domain_regex, host_regex, import_email_validator, int_domain_regex, multi_host_url_regex, stricturl; 34 imports; method: AnyUrl.__get_validators__, AnyUrl.__init__, AnyUrl.__modify_schema__, AnyUrl.__new__, AnyUrl.__repr__, AnyUrl._build_url; module: networks; rationale: [TODO] Needed to generic "Parts" for "Replica Set", "Sharded Cluster", and other mongod
**parse.py** — class: Protocol; function: load_file, load_str_bytes; 8 imports; module: parse
**schema.py** — class: SkipField; function: _apply_modify_schema, add_field_type_to_schema, encode_default, enum_process_schema, field_schema, field_singleton_schema; 90 imports; method: SkipField.__init__; module: schema
**tools.py** — function: _generate_parsing_type_name, _get_parsing_type, parse_file_as, parse_obj_as, parse_raw_as, schema_json_of; 17 imports; module: tools
**types.py** — class: ByteSize, ConstrainedBytes, ConstrainedDate, ConstrainedDecimal, ConstrainedFloat, ConstrainedFrozenSet; function: _registered, conbytes, condate, condecimal, confloat, confrozenset; 57 imports; method: ByteSize.__get_validators__, ByteSize.human_readable, ByteSize.to, ByteSize.validate, ConstrainedBytes.__get_validators__, ConstrainedBytes.__modify_schema__; module: types
**typing.py** — function: _check_classvar, _check_finalvar, _check_typeddict_special, all_literal_values, display_as_type, get_class; 43 imports; module: typing
**utils.py** — class: ClassAttribute, GetterDict, PyObjectStr, Representation, ValueItems; function: _get_union_alias_and_all_values, all_identical, almost_equal_floats, assert_never, deep_update, generate_model_signature; 59 imports; method: ClassAttribute.__get__, ClassAttribute.__init__, GetterDict.__contains__, GetterDict.__eq__, GetterDict.__getitem__, GetterDict.__init__; module: utils; rationale: [NOTE] including ModuleType will differ from behaviour of deepcopy by not producing err, [TODO] replace annotation with actual expected types once #1055 solved
**validators.py** — class: IfConfig; function: any_class_validator, anystr_length_validator, anystr_lower, anystr_strip_whitespace, anystr_upper, bool_validator; 67 imports; method: IfConfig.__init__, IfConfig.check; module: validators
**version.py** — function: version_info; 5 imports; module: version
**validate_call_decorator.py** — function: _check_function_type, validate_call; 15 imports; module: validate_call_decorator
**validators.py** — 1 imports; module: validators
**version.py** — function: _ensure_pydantic_core_version, check_pydantic_core_version, parse_mypy_version, version_info, version_short; 9 imports; module: version
**warnings.py** — class: ArbitraryTypeWarning, CoreSchemaGenerationWarning, GenericBeforeBaseModelWarning, PydanticDeprecatedSince20, PydanticDeprecatedSince210, PydanticDeprecatedSince211; 2 imports; method: PydanticDeprecatedSince20.__init__, PydanticDeprecatedSince210.__init__, PydanticDeprecatedSince211.__init__, PydanticDeprecatedSince212.__init__, PydanticDeprecatedSince26.__init__, PydanticDeprecatedSince29.__init__; module: warnings
**__init__.py** — class: ErrorDetails, ErrorTypeInfo, InitErrorDetails, MultiHostHost; 33 imports; module: __init__
**core_schema.py** — class: AfterValidatorFunctionSchema, AnySchema, ArgumentsParameter, ArgumentsSchema, ArgumentsV3Parameter, ArgumentsV3Schema; function: __getattr__, _dict_not_none, any_schema, arguments_parameter, arguments_schema, arguments_v3_parameter; 28 imports; method: FieldSerializationInfo.field_name, SerializationInfo.__repr__, SerializationInfo.__str__, SerializationInfo.by_alias, SerializationInfo.context, SerializationInfo.exclude; module: core_schema
**__init__.py** — 32 imports; module: __init__
**exceptions.py** — class: SettingsError; module: exceptions
**main.py** — class: BaseSettings, CliApp, SettingsConfigDict; 42 imports; method: BaseSettings.__init__, BaseSettings._settings_build_values, BaseSettings._settings_init_sources, BaseSettings._settings_restore_init_kwarg_names, BaseSettings._settings_warn_unused_config_keys, BaseSettings.settings_customise_sources; module: main; rationale: [NOTE] when adding new parameters, make sure to use `object` instead of `Any` to avoid 
**__init__.py** — 38 imports; module: __init__
**base.py** — class: ConfigFileSourceMixin, DefaultSettingsSource, InitSettingsSource, PydanticBaseEnvSettingsSource, PydanticBaseSettingsSource; function: get_subcommand; 38 imports; method: ConfigFileSourceMixin._read_file, ConfigFileSourceMixin._read_files, DefaultSettingsSource.__call__, DefaultSettingsSource.__init__, DefaultSettingsSource.__repr__, DefaultSettingsSource.get_field_value; module: base; rationale: [NOTE] If populate_by_name is True and the provided key is the field name, but
**__init__.py** — 19 imports; module: __init__
**aws.py** — class: AWSSecretsManagerSettingsSource; function: import_aws_secrets_manager; 9 imports; method: AWSSecretsManagerSettingsSource.__init__, AWSSecretsManagerSettingsSource.__repr__, AWSSecretsManagerSettingsSource._load_env_vars; module: aws
**azure.py** — class: AzureKeyVaultMapping, AzureKeyVaultSettingsSource; function: import_azure_key_vault; 11 imports; method: AzureKeyVaultMapping.__getitem__, AzureKeyVaultMapping.__init__, AzureKeyVaultMapping.__iter__, AzureKeyVaultMapping.__len__, AzureKeyVaultMapping._load_remote, AzureKeyVaultSettingsSource.__init__; module: azure
**cli.py** — class: CliMutuallyExclusiveGroup, CliSettingsSource, _CliArg, _CliInternalArgParser; function: _collect_sub_models, _get_model_description; 69 imports; method: CliSettingsSource.__call__, CliSettingsSource.__init__, CliSettingsSource._add_default_help, CliSettingsSource._add_parser_alias_paths, CliSettingsSource._add_parser_args, CliSettingsSource._add_parser_submodels; module: cli; rationale: [NOTE] CLI positional args are always strictly required at the CLI. Therefore, use fiel, [NOTE] prepend 'no-' for boolean optional action flag if model_default value is False a
**dotenv.py** — class: DotEnvSettingsSource; function: read_env_file; 19 imports; method: DotEnvSettingsSource.__call__, DotEnvSettingsSource.__init__, DotEnvSettingsSource.__repr__, DotEnvSettingsSource._load_env_vars, DotEnvSettingsSource._read_env_file, DotEnvSettingsSource._read_env_files; module: dotenv
**env.py** — class: EnvSettingsSource; 29 imports; method: EnvSettingsSource.__init__, EnvSettingsSource.__repr__, EnvSettingsSource._coerce_env_val_strict, EnvSettingsSource._field_is_complex, EnvSettingsSource._load_env_vars, EnvSettingsSource.explode_env_vars; module: env
**gcp.py** — class: GoogleSecretManagerMapping, GoogleSecretManagerSettingsSource; function: import_gcp_secret_manager; 14 imports; method: GoogleSecretManagerMapping.__getitem__, GoogleSecretManagerMapping.__init__, GoogleSecretManagerMapping.__iter__, GoogleSecretManagerMapping.__len__, GoogleSecretManagerMapping._gcp_project_path, GoogleSecretManagerMapping._get_secret_value; module: gcp
**json.py** — class: JsonConfigSettingsSource; 10 imports; method: JsonConfigSettingsSource.__init__, JsonConfigSettingsSource.__repr__, JsonConfigSettingsSource._read_file; module: json
**nested_secrets.py** — class: NestedSecretsSettingsSource; function: first_not_none; 17 imports; method: NestedSecretsSettingsSource.__init__, NestedSecretsSettingsSource.__repr__, NestedSecretsSettingsSource._iter_secret_files, NestedSecretsSettingsSource.load_secrets, NestedSecretsSettingsSource.validate_secrets_path; module: nested_secrets
**pyproject.py** — class: PyprojectTomlConfigSettingsSource; 5 imports; method: PyprojectTomlConfigSettingsSource.__init__, PyprojectTomlConfigSettingsSource._pick_pyproject_toml_file; module: pyproject
**secrets.py** — class: SecretsSettingsSource; 13 imports; method: SecretsSettingsSource.__call__, SecretsSettingsSource.__init__, SecretsSettingsSource.__repr__, SecretsSettingsSource.find_case_path, SecretsSettingsSource.get_field_value; module: secrets
**toml.py** — class: TomlConfigSettingsSource; function: import_toml; 12 imports; method: TomlConfigSettingsSource.__init__, TomlConfigSettingsSource.__repr__, TomlConfigSettingsSource._read_file; module: toml
**yaml.py** — class: YamlConfigSettingsSource; function: import_yaml; 10 imports; method: YamlConfigSettingsSource.__init__, YamlConfigSettingsSource.__repr__, YamlConfigSettingsSource._read_file, YamlConfigSettingsSource._traverse_nested_section; module: yaml
**types.py** — class: EnvNoneType, ForceDecode, NoDecode, SecretVersion, _CliDualFlag, _CliExplicitFlag; 8 imports; method: SecretVersion.__init__, SecretVersion.__repr__; module: types
**utils.py** — function: _annotation_contains_types, _annotation_enum_name_to_val, _annotation_enum_val_to_name, _annotation_is_complex, _annotation_is_complex_inner, _get_alias_names; 30 imports; module: utils
**utils.py** — function: _lenient_issubclass, path_type_label; 6 imports; module: utils
**version.py** — module: version
**__init__.py** — function: format, highlight, lex; 4 imports; module: __init__
**__main__.py** — 2 imports; module: __main__
**cmdline.py** — class: HelpFormatter; function: _parse_filters, _parse_options, _print_help, _print_list, _print_list_as_json, main; 38 imports; method: HelpFormatter.__init__; module: cmdline
**console.py** — function: ansiformat, colorize, reset_color; module: console
**filter.py** — class: Filter, FunctionFilter; function: apply_filters, simplefilter; method: Filter.__init__, Filter.filter, FunctionFilter.__init__, FunctionFilter.filter; module: filter
**__init__.py** — class: CodeTagFilter, ErrorToken, GobbleFilter, KeywordCaseFilter, NameHighlightFilter, RaiseOnErrorTokenFilter; function: _replace_special, find_filter_class, get_all_filters, get_filter_by_name; 16 imports; method: CodeTagFilter.__init__, CodeTagFilter.filter, GobbleFilter.__init__, GobbleFilter.filter, GobbleFilter.gobble, KeywordCaseFilter.__init__; module: __init__
**formatter.py** — class: Formatter; function: _lookup_style; 3 imports; method: Formatter.__class_getitem__, Formatter.__init__, Formatter.format, Formatter.get_style_defs; module: formatter
**__init__.py** — class: _automodule; function: _fn_matches, _load_formatters, find_formatter_class, get_all_formatters, get_formatter_by_name, get_formatter_for_filename; 8 imports; method: _automodule.__getattr__; module: __init__
**_mapping.py** — module: _mapping
**bbcode.py** — class: BBCodeFormatter; 2 imports; method: BBCodeFormatter.__init__, BBCodeFormatter._make_styles, BBCodeFormatter.format_unencoded; module: bbcode
**groff.py** — class: GroffFormatter; 4 imports; method: GroffFormatter.__init__, GroffFormatter._define_colors, GroffFormatter._escape_chars, GroffFormatter._make_styles, GroffFormatter._wrap_line, GroffFormatter._write_lineno; module: groff
**html.py** — class: HtmlFormatter; function: _get_ttype_class, escape_html, webify; 14 imports; method: HtmlFormatter.__init__, HtmlFormatter._create_stylesheet, HtmlFormatter._decodeifneeded, HtmlFormatter._format_lines, HtmlFormatter._get_css_class, HtmlFormatter._get_css_classes; module: html
**img.py** — class: BmpImageFormatter, FontManager, FontNotFound, GifImageFormatter, ImageFormatter, JpgImageFormatter; 13 imports; method: FontManager.__init__, FontManager._create_mac, FontManager._create_nix, FontManager._create_win, FontManager._get_mac_font_path, FontManager._get_nix_font_path; module: img; rationale: [TODO] make sure tab expansion happens earlier in the chain.  It
**irc.py** — class: IRCFormatter; function: ircformat; 12 imports; method: IRCFormatter.__init__, IRCFormatter._write_lineno, IRCFormatter.format_unencoded; module: irc
**latex.py** — class: LatexEmbeddedLexer, LatexFormatter; function: _get_ttype_name, escape_tex; 8 imports; method: LatexEmbeddedLexer.__init__, LatexEmbeddedLexer._filter_to, LatexEmbeddedLexer._find_escape_tokens, LatexEmbeddedLexer._find_safe_escape_tokens, LatexEmbeddedLexer.get_tokens_unprocessed, LatexFormatter.__init__; module: latex; rationale: [TODO] add support for background colors
**other.py** — class: NullFormatter, RawTokenFormatter, TestcaseFormatter; 6 imports; method: NullFormatter.format, RawTokenFormatter.__init__, RawTokenFormatter.format, TestcaseFormatter.__init__, TestcaseFormatter.format; module: other
**pangomarkup.py** — class: PangoMarkupFormatter; function: escape_special_chars; 1 imports; method: PangoMarkupFormatter.__init__, PangoMarkupFormatter.format_unencoded; module: pangomarkup
**rtf.py** — class: RtfFormatter; 7 imports; method: RtfFormatter.__init__, RtfFormatter._create_color_mapping, RtfFormatter._escape, RtfFormatter._escape_text, RtfFormatter._hl_open_str, RtfFormatter._lineno_template; module: rtf
**svg.py** — class: SvgFormatter; function: escape_html; 4 imports; method: SvgFormatter.__init__, SvgFormatter._get_style, SvgFormatter.format_unencoded; module: svg
**terminal.py** — class: TerminalFormatter; 13 imports; method: TerminalFormatter.__init__, TerminalFormatter._get_color, TerminalFormatter._write_lineno, TerminalFormatter.format, TerminalFormatter.format_unencoded; module: terminal
**terminal256.py** — class: EscapeSequence, Terminal256Formatter, TerminalTrueColorFormatter; 3 imports; method: EscapeSequence.__init__, EscapeSequence.color_string, EscapeSequence.escape, EscapeSequence.reset_string, EscapeSequence.true_color_string, Terminal256Formatter.__init__; module: terminal256
**lexer.py** — class: DelegatingLexer, ExtendedRegexLexer, Lexer, LexerContext, LexerMeta, ProfilingRegexLexer; function: bygroups, do_insertions, using; 19 imports; method: DelegatingLexer.__init__, DelegatingLexer.get_tokens_unprocessed, ExtendedRegexLexer.get_tokens_unprocessed, Lexer.__init__, Lexer.__repr__, Lexer._preprocess_lexer_input; module: lexer; rationale: [XXX] cache that somehow, [XXX] cache that somehow
**__init__.py** — class: _automodule; function: _fn_matches, _iter_lexerclasses, _load_lexers, find_lexer_class, find_lexer_class_by_name, find_lexer_class_for_filename; 10 imports; method: _automodule.__getattr__; module: __init__
**_ada_builtins.py** — module: _ada_builtins
**_asy_builtins.py** — module: _asy_builtins
**_cl_builtins.py** — module: _cl_builtins
**_cocoa_builtins.py** — 2 imports; module: _cocoa_builtins
**_csound_builtins.py** — module: _csound_builtins
**_css_builtins.py** — module: _css_builtins
**_googlesql_builtins.py** — module: _googlesql_builtins
**_julia_builtins.py** — module: _julia_builtins
**_lasso_builtins.py** — module: _lasso_builtins
**_lilypond_builtins.py** — module: _lilypond_builtins
**_lua_builtins.py** — 3 imports; module: _lua_builtins
**_luau_builtins.py** — module: _luau_builtins
**_mapping.py** — module: _mapping
**_mql_builtins.py** — module: _mql_builtins
**_mysql_builtins.py** — 3 imports; module: _mysql_builtins
**_openedge_builtins.py** — module: _openedge_builtins
**_php_builtins.py** — 7 imports; module: _php_builtins
**_postgres_builtins.py** — 3 imports; module: _postgres_builtins
**_qlik_builtins.py** — module: _qlik_builtins
**_scheme_builtins.py** — module: _scheme_builtins
**_scilab_builtins.py** — 3 imports; module: _scilab_builtins
**_sourcemod_builtins.py** — 3 imports; module: _sourcemod_builtins
**_sql_builtins.py** — module: _sql_builtins
**_stan_builtins.py** — module: _stan_builtins
**_stata_builtins.py** — module: _stata_builtins
**_tsql_builtins.py** — module: _tsql_builtins
**_usd_builtins.py** — module: _usd_builtins
**_vbscript_builtins.py** — module: _vbscript_builtins
**_vim_builtins.py** — function: _getauto, _getcommand, _getoption; module: _vim_builtins
**actionscript.py** — class: ActionScript3Lexer, ActionScriptLexer, MxmlLexer; 16 imports; method: ActionScript3Lexer.analyse_text, ActionScriptLexer.analyse_text; module: actionscript
**ada.py** — class: AdaLexer; 18 imports; module: ada; rationale: [TODO] use Name.Namespace if appropriate.  This needs
**agile.py** — 21 imports; module: agile
**algebra.py** — class: BCLexer, GAPConsoleLexer, GAPLexer, MathematicaLexer, MuPADLexer; 16 imports; method: GAPConsoleLexer.analyse_text, GAPConsoleLexer.get_tokens_unprocessed, GAPLexer.analyse_text, MathematicaLexer._multi_escape; module: algebra
**ambient.py** — class: AmbientTalkLexer; 13 imports; module: ambient
**amdgpu.py** — class: AMDGPULexer; 9 imports; module: amdgpu
**ampl.py** — class: AmplLexer; 14 imports; module: ampl
**apdlexer.py** — class: apdlexer; 15 imports; module: apdlexer
**apl.py** — class: APLLexer; 9 imports; module: apl
**archetype.py** — class: AdlLexer, AtomsLexer, CadlLexer, OdinLexer; 16 imports; module: archetype
**arrow.py** — class: ArrowLexer; 12 imports; module: arrow
**arturo.py** — class: ArturoLexer; 19 imports; method: ArturoLexer.__init__, ArturoLexer.handle_annotated_strings; module: arturo; rationale: [NOTE] Attributes can be labeled too, [NOTE] Literals can be labeled too
**asc.py** — class: AscLexer; 9 imports; method: AscLexer.analyse_text; module: asc
**asm.py** — class: CObjdumpLexer, Ca65Lexer, CppObjdumpLexer, DObjdumpLexer, Dasm16Lexer, GasLexer; function: _objdump_lexer_tokens; 21 imports; method: CObjdumpLexer.__init__, Ca65Lexer.analyse_text, CppObjdumpLexer.__init__, DObjdumpLexer.__init__, Dasm16Lexer.guess_identifier, GasLexer.analyse_text; module: asm
**asn1.py** — class: Asn1Lexer; function: word_sequences; 12 imports; module: asn1
**automation.py** — class: AutoItLexer, AutohotkeyLexer; 12 imports; module: automation
**bare.py** — class: BareLexer; 9 imports; module: bare
**basic.py** — class: BBCBasicLexer, BlitzBasicLexer, BlitzMaxLexer, CbmBasicV2Lexer, MonkeyLexer, QBasicLexer; 17 imports; method: BBCBasicLexer.analyse_text, CbmBasicV2Lexer.analyse_text, QBasicLexer.analyse_text; module: basic; rationale: [XXX] use words() here
**bdd.py** — class: BddLexer; 10 imports; method: BddLexer.analyse_text; module: bdd
**berry.py** — class: BerryLexer; 12 imports; module: berry
**bibtex.py** — class: BSTLexer, BibTeXLexer; 14 imports; method: BibTeXLexer.close_brace_callback, BibTeXLexer.open_brace_callback; module: bibtex
**blueprint.py** — class: BlueprintLexer; 13 imports; module: blueprint
**boa.py** — class: BoaLexer; 10 imports; module: boa
**bqn.py** — class: BQNLexer; 9 imports; module: bqn
**business.py** — class: ABAPLexer, CobolFreeformatLexer, CobolLexer, GoodDataCLLexer, MaqlLexer, OpenEdgeLexer; 16 imports; method: OpenEdgeLexer.analyse_text; module: business
**c_cpp.py** — class: CFamilyLexer, CLexer, CppLexer; 19 imports; method: CFamilyLexer.__init__, CFamilyLexer.get_tokens_unprocessed, CLexer.analyse_text, CppLexer.analyse_text; module: c_cpp
**c_like.py** — class: ArduinoLexer, CharmciLexer, ClayLexer, CudaLexer, ECLexer, MqlLexer; 19 imports; method: ArduinoLexer.get_tokens_unprocessed, CudaLexer.get_tokens_unprocessed, SwigLexer.analyse_text; module: c_like; rationale: [TODO] "correctly" parse complex code attributes
**capnproto.py** — class: CapnProtoLexer; 8 imports; module: capnproto
**carbon.py** — class: CarbonLexer; 12 imports; method: CarbonLexer.analyse_text; module: carbon
**cddl.py** — class: CddlLexer; 13 imports; module: cddl
**chapel.py** — class: ChapelLexer; 12 imports; module: chapel
**clean.py** — class: CleanLexer; 15 imports; module: clean
**codeql.py** — class: CodeQLLexer; 11 imports; module: codeql
**comal.py** — class: Comal80Lexer; 11 imports; module: comal
**compiled.py** — 34 imports; module: compiled
**configs.py** — class: ApacheConfLexer, AugeasLexer, Cfengine3Lexer, DesktopLexer, DockerLexer, IniLexer; function: _rx_indent; 23 imports; method: DesktopLexer.analyse_text, IniLexer.analyse_text, KconfigLexer.call_indent, KconfigLexer.do_indent, RegeditLexer.analyse_text, SingularityLexer.analyse_text; module: configs; rationale: [XXX] /integer is a subnet mark, but what is /IP ?
**console.py** — class: PyPyLogLexer, VCTreeStatusLexer; 12 imports; module: console
**cplint.py** — class: CplintLexer; 9 imports; module: cplint
**crystal.py** — class: CrystalLexer; 16 imports; method: CrystalLexer.gen_crystalstrings_rules, CrystalLexer.heredoc_callback; module: crystal
**csound.py** — class: CsoundDocumentLexer, CsoundLexer, CsoundOrchestraLexer, CsoundScoreLexer; 23 imports; method: CsoundOrchestraLexer.name_callback, CsoundOrchestraLexer.opcode_name_callback; module: csound
**css.py** — class: CssLexer, LessCssLexer, SassLexer, ScssLexer; function: _indentation, _starts_block; 18 imports; module: css; rationale: [FIXME] It's not currently possible to simply do the following,, [TODO] broken, and prone to infinite loops.
**d.py** — class: CrocLexer, DLexer, MiniDLexer; 11 imports; module: d
**dalvik.py** — class: SmaliLexer; 12 imports; method: SmaliLexer.analyse_text; module: dalvik
**data.py** — class: JsonBareObjectLexer, JsonLdLexer, JsonLexer, YamlLexer, YamlLexerContext; 14 imports; method: JsonLdLexer.get_tokens_unprocessed, JsonLexer.get_tokens_unprocessed, YamlLexer.get_tokens_unprocessed, YamlLexer.parse_block_scalar_empty_line, YamlLexer.parse_block_scalar_indent, YamlLexer.parse_plain_scalar_indent; module: data
**dax.py** — class: DaxLexer; 10 imports; module: dax
**devicetree.py** — class: DevicetreeLexer; 14 imports; module: devicetree
**diff.py** — class: DarcsPatchLexer, DiffLexer, WDiffLexer; 12 imports; method: DiffLexer.analyse_text; module: diff
**dns.py** — class: DnsZoneLexer; 13 imports; method: DnsZoneLexer.analyse_text; module: dns
**dotnet.py** — class: BooLexer, CSharpAspxLexer, CSharpLexer, FSharpLexer, GenericAspxLexer, NemerleLexer; 23 imports; method: CSharpAspxLexer.__init__, CSharpAspxLexer.analyse_text, CSharpLexer.__init__, FSharpLexer.analyse_text, NemerleLexer.__init__, NemerleLexer.analyse_text; module: dotnet
**dsls.py** — class: AlloyLexer, CrmshLexer, FlatlineLexer, MscgenLexer, PanLexer, ProtoBufLexer; 19 imports; method: RslLexer.analyse_text, SnowballLexer.__init__, SnowballLexer._reset_stringescapes, SnowballLexer._string, SnowballLexer._stringescapes, SnowballLexer.get_tokens_unprocessed; module: dsls
**dylan.py** — class: DylanConsoleLexer, DylanLexer, DylanLidLexer; 17 imports; method: DylanConsoleLexer.get_tokens_unprocessed, DylanLexer.get_tokens_unprocessed; module: dylan
**ecl.py** — class: ECLLexer; 13 imports; method: ECLLexer.analyse_text; module: ecl
**eiffel.py** — class: EiffelLexer; 12 imports; module: eiffel
**elm.py** — class: ElmLexer; 11 imports; module: elm
**elpi.py** — class: ElpiLexer; 13 imports; module: elpi
**email.py** — class: EmailHeaderLexer, EmailLexer; 11 imports; method: EmailHeaderLexer.__init__, EmailHeaderLexer.get_x_header_tokens, EmailLexer.__init__; module: email
**erlang.py** — class: ElixirConsoleLexer, ElixirLexer, ErlangLexer, ErlangShellLexer; function: gen_elixir_sigstr_rules, gen_elixir_string_rules; 18 imports; method: ElixirConsoleLexer.get_tokens_unprocessed, ElixirLexer.gen_elixir_sigil_rules, ElixirLexer.get_tokens_unprocessed, ErlangShellLexer.get_tokens_unprocessed; module: erlang
**esoteric.py** — class: AheuiLexer, BefungeLexer, BrainfuckLexer, CAmkESLexer, CapDLLexer, RedcodeLexer; 13 imports; method: BrainfuckLexer.analyse_text; module: esoteric
**ezhil.py** — class: EzhilLexer; 12 imports; method: EzhilLexer.__init__, EzhilLexer.analyse_text; module: ezhil
**factor.py** — class: FactorLexer; 12 imports; module: factor
**fantom.py** — class: FantomLexer; 18 imports; method: FantomLexer.s; module: fantom; rationale: [TODO] highlight references in fandocs, [TODO] remove copy/paste str/uri
**felix.py** — class: FelixLexer; 15 imports; module: felix
**fift.py** — class: FiftLexer; 8 imports; module: fift
**floscript.py** — class: FloScriptLexer; 12 imports; method: FloScriptLexer.innerstring_rules; module: floscript
**forth.py** — class: ForthLexer; 10 imports; method: ForthLexer.analyse_text; module: forth
**fortran.py** — class: FortranFixedLexer, FortranLexer; 16 imports; method: FortranFixedLexer._lex_fortran; module: fortran
**foxpro.py** — class: FoxProLexer; 9 imports; module: foxpro
**freefem.py** — class: FreeFemLexer; 5 imports; method: FreeFemLexer.get_tokens_unprocessed; module: freefem
**func.py** — class: FuncLexer; 12 imports; module: func
**functional.py** — 16 imports; module: functional
**futhark.py** — class: FutharkLexer; 11 imports; module: futhark
**gcodelexer.py** — class: GcodeLexer; 7 imports; module: gcodelexer
**gdscript.py** — class: GDScriptLexer; 16 imports; method: GDScriptLexer.analyse_text, GDScriptLexer.innerstring_rules; module: gdscript
**gleam.py** — class: GleamLexer; 11 imports; module: gleam
**go.py** — class: GoLexer; 12 imports; module: go
**grammar_notation.py** — class: AbnfLexer, BnfLexer, JsgfLexer, PegLexer; 16 imports; module: grammar_notation
**graph.py** — class: CypherLexer; 15 imports; module: graph
**graphics.py** — class: AsymptoteLexer, GLShaderLexer, GnuplotLexer, HLSLShaderLexer, PostScriptLexer, PovrayLexer; function: _shortened, _shortened_many; 18 imports; method: AsymptoteLexer.get_tokens_unprocessed, PovrayLexer.analyse_text; module: graphics
**graphql.py** — class: GraphQLLexer; 12 imports; module: graphql
**graphviz.py** — class: GraphvizLexer; 10 imports; module: graphviz
**gsql.py** — class: GSQLLexer; 15 imports; module: gsql
**hare.py** — class: HareLexer; 11 imports; module: hare
**haskell.py** — class: AgdaLexer, CryptolLexer, HaskellLexer, HspecLexer, IdrisLexer, KokaLexer; 21 imports; method: CryptolLexer.get_tokens_unprocessed, LiterateAgdaLexer.__init__, LiterateCryptolLexer.__init__, LiterateHaskellLexer.__init__, LiterateIdrisLexer.__init__, LiterateLexer.__init__; module: haskell; rationale: [NOTE] the next four states are shared in the AgdaLexer; make sure, [NOTE] the next four states are shared in the AgdaLexer; make sure, [TODO] these don't match the comments in docs, remove.
**haxe.py** — class: HaxeLexer, HxmlLexer; 16 imports; method: HaxeLexer.analyse_text, HaxeLexer.preproc_callback; module: haxe
**hdl.py** — class: SystemVerilogLexer, VerilogLexer, VhdlLexer; 16 imports; method: VerilogLexer.analyse_text; module: hdl
**hexdump.py** — class: HexdumpLexer; 8 imports; module: hexdump
**html.py** — class: DtdLexer, HamlLexer, HtmlLexer, PugLexer, ScamlLexer, UrlEncodedLexer; 25 imports; method: DtdLexer.analyse_text, HtmlLexer.analyse_text, XmlLexer.analyse_text, XsltLexer.analyse_text, XsltLexer.get_tokens_unprocessed; module: html; rationale: [NOTE] this allows tag names not used in HTML like <x:with-dash>,
**idl.py** — class: IDLLexer; 12 imports; method: IDLLexer.analyse_text; module: idl
**igor.py** — class: IgorLexer; 9 imports; module: igor
**inferno.py** — class: LimboLexer; 13 imports; method: LimboLexer.analyse_text; module: inferno
**installers.py** — class: DebianControlLexer, DebianSourcesLexer, NSISLexer, RPMSpecLexer, SourcesListLexer; 17 imports; method: SourcesListLexer.analyse_text; module: installers
**int_fiction.py** — class: Inform6Lexer, Inform6TemplateLexer, Inform7Lexer, Tads3Lexer; 18 imports; method: Inform6Lexer.analyse_text, Inform6Lexer.get_tokens_unprocessed, Inform6TemplateLexer.get_tokens_unprocessed, Inform7Lexer.__init__, Tads3Lexer._make_attribute_value_state, Tads3Lexer._make_string_state; module: int_fiction
**iolang.py** — class: IoLexer; 8 imports; module: iolang
**j.py** — class: JLexer; 12 imports; module: j
**javascript.py** — class: CoffeeScriptLexer, DartLexer, EarlGreyLexer, JavascriptLexer, JuttleLexer, KalLexer; 28 imports; method: LassoLexer.__init__, LassoLexer.analyse_text, LassoLexer.get_tokens_unprocessed, NodeConsoleLexer.get_tokens_unprocessed, ObjectiveJLexer.analyse_text; module: javascript; rationale: [TODO] should this include single-line comments and allow nesting strings?
**jmespath.py** — class: JMESPathLexer; 11 imports; module: jmespath
**jslt.py** — class: JSLTLexer; 11 imports; module: jslt
**json5.py** — class: Json5Lexer; function: quoted_field_name, string_rules; 10 imports; module: json5
**jsonnet.py** — class: JsonnetLexer; function: quoted_field_name, string_rules; 12 imports; module: jsonnet
**jsx.py** — class: JsxLexer, TsxLexer; 13 imports; module: jsx
**julia.py** — class: JuliaConsoleLexer, JuliaLexer; 22 imports; method: JuliaConsoleLexer.get_tokens_unprocessed, JuliaLexer.analyse_text; module: julia; rationale: [FIXME] This escape pattern is not perfect.
**jvm.py** — class: AspectJLexer, CeylonLexer, ClojureLexer, ClojureScriptLexer, GoloLexer, GosuLexer; 21 imports; method: AspectJLexer.get_tokens_unprocessed, GosuTemplateLexer.get_tokens_unprocessed, GroovyLexer.analyse_text, JasminLexer.analyse_text; module: jvm; rationale: [TODO] make tests pass without \s+
**kuin.py** — class: KuinLexer; 15 imports; module: kuin
**kusto.py** — class: KustoLexer; 9 imports; module: kusto
**ldap.py** — class: LdaprcLexer, LdifLexer; 14 imports; module: ldap
**lean.py** — class: Lean3Lexer, Lean4Lexer; 12 imports; method: Lean3Lexer.analyse_text, Lean4Lexer.analyse_text; module: lean
**lilypond.py** — class: LilyPondLexer; function: builtin_words; 28 imports; method: LilyPondLexer.get_tokens_unprocessed; module: lilypond
**lisp.py** — class: CPSALexer, CommonLispLexer, EmacsLispLexer, FennelLexer, HyLexer, JanetLexer; 27 imports; method: CommonLispLexer.__init__, CommonLispLexer.analyse_text, CommonLispLexer.get_tokens_unprocessed, EmacsLispLexer.get_tokens_unprocessed, HyLexer._multi_escape, HyLexer.analyse_text; module: lisp; rationale: [XXX] gets too slow, [XXX] this form not usable to pass to `suffix=`
**macaulay2.py** — class: Macaulay2Lexer; 7 imports; module: macaulay2
**make.py** — class: BaseMakefileLexer, CMakeLexer, MakefileLexer; 16 imports; method: CMakeLexer.analyse_text, MakefileLexer.analyse_text, MakefileLexer.get_tokens_unprocessed; module: make
**maple.py** — class: MapleLexer; 11 imports; method: MapleLexer.analyse_text, MapleLexer.delayed_callback; module: maple
**markup.py** — class: BBCodeLexer, GroffLexer, MarkdownLexer, MoinWikiLexer, MozPreprocCssLexer, MozPreprocHashLexer; 30 imports; method: GroffLexer.analyse_text, MarkdownLexer.__init__, MarkdownLexer._handle_codeblock, MozPreprocCssLexer.__init__, MozPreprocJavascriptLexer.__init__, MozPreprocXulLexer.__init__; module: markup; rationale: [FIXME] Use ABC lexer in the future, [FIXME] aren't the offsets wrong?, [TODO] language-dependent syntax highlighting (see Markdown lexer)
**math.py** — 15 imports; module: math
**matlab.py** — class: MatlabLexer, MatlabSessionLexer, OctaveLexer, ScilabLexer; 19 imports; method: MatlabLexer.analyse_text, MatlabSessionLexer.get_tokens_unprocessed, OctaveLexer.analyse_text, ScilabLexer.analyse_text; module: matlab
**maxima.py** — class: MaximaLexer; 12 imports; method: MaximaLexer.analyse_text; module: maxima
**meson.py** — class: MesonLexer; 11 imports; module: meson
**mime.py** — class: MIMELexer; 12 imports; method: MIMELexer.__init__, MIMELexer.get_body_tokens, MIMELexer.get_bodypart_tokens, MIMELexer.get_content_type_subtokens, MIMELexer.get_header_tokens, MIMELexer.store_content_transfer_encoding; module: mime
**minecraft.py** — class: MCFunctionLexer, MCSchemaLexer, SNBTLexer; 14 imports; module: minecraft; rationale: [NOTE] stringified keys still work
**mips.py** — class: MIPSLexer; 8 imports; module: mips; rationale: [TODO] add '*.s' and '*.asm', which will require designing an analyse_text
**ml.py** — class: FStarLexer, OcamlLexer, OpaLexer, ReasonLexer, SMLLexer; 15 imports; method: SMLLexer.end_id_callback, SMLLexer.id_callback, SMLLexer.long_id_callback, SMLLexer.stringy; module: ml
**modeling.py** — class: BugsLexer, JagsLexer, ModelicaLexer, StanLexer; 17 imports; method: BugsLexer.analyse_text, JagsLexer.analyse_text, StanLexer.analyse_text; module: modeling
**modula2.py** — class: Modula2Lexer; 14 imports; method: Modula2Lexer.__init__, Modula2Lexer.analyse_text, Modula2Lexer.get_dialect_from_dialect_tag, Modula2Lexer.get_tokens_unprocessed, Modula2Lexer.set_dialect; module: modula2
**mojo.py** — class: MojoLexer; 20 imports; method: MojoLexer.analyse_text, MojoLexer.fstring_rules, MojoLexer.innerstring_rules; module: mojo
**monte.py** — class: MonteLexer; 12 imports; module: monte
**mosel.py** — class: MoselLexer; 10 imports; module: mosel
**ncl.py** — class: NCLLexer; 12 imports; module: ncl
**nimrod.py** — class: NimrodLexer; 14 imports; method: NimrodLexer.underscorize; module: nimrod
**nit.py** — class: NitLexer; 10 imports; module: nit
**nix.py** — class: NixLexer; 12 imports; method: NixLexer.analyse_text; module: nix; rationale: [TODO] let/in, [TODO] we should probably escape also here ''${ \${
**numbair.py** — class: NumbaIRLexer; 11 imports; module: numbair
**oberon.py** — class: ComponentPascalLexer; 12 imports; method: ComponentPascalLexer.analyse_text; module: oberon; rationale: [TODO] nested comments (* (* ... *) ... (* ... *) *) not supported!
**objective.py** — class: LogosLexer, ObjectiveCLexer, ObjectiveCppLexer, SwiftLexer; function: objective; 24 imports; method: LogosLexer.analyse_text, SwiftLexer.get_tokens_unprocessed; module: objective
**ooc.py** — class: OocLexer; 11 imports; module: ooc; rationale: [NOTE] %= not listed on https://ooc-lang.github.io/docs/lang/operators/
**openscad.py** — class: OpenScadLexer; 14 imports; module: openscad
**other.py** — 47 imports; module: other
**parasail.py** — class: ParaSailLexer; 12 imports; module: parasail
**parsers.py** — class: AntlrActionScriptLexer, AntlrCSharpLexer, AntlrCppLexer, AntlrJavaLexer, AntlrLexer, AntlrObjectiveCLexer; 26 imports; method: AntlrActionScriptLexer.__init__, AntlrActionScriptLexer.analyse_text, AntlrCSharpLexer.__init__, AntlrCSharpLexer.analyse_text, AntlrCppLexer.__init__, AntlrCppLexer.analyse_text; module: parsers
**pascal.py** — class: DelphiLexer, PortugolLexer; 15 imports; method: DelphiLexer.__init__, DelphiLexer.get_tokens_unprocessed, PortugolLexer.__init__, PortugolLexer.get_tokens_unprocessed; module: pascal; rationale: [XXX] those aren't global. but currently we know no way for defining
**pawn.py** — class: PawnLexer, SourcePawnLexer; 11 imports; method: PawnLexer.analyse_text, SourcePawnLexer.__init__, SourcePawnLexer.get_tokens_unprocessed; module: pawn
**pddl.py** — class: PddlLexer; 10 imports; module: pddl
**perl.py** — class: Perl6Lexer, PerlLexer; 19 imports; method: Perl6Lexer.__init__, Perl6Lexer._build_word_match, Perl6Lexer.analyse_text, Perl6Lexer.brackets_callback, Perl6Lexer.closing_brace_callback, Perl6Lexer.embedded_perl6_callback; module: perl; rationale: [TODO] give this to a perl guy who knows how to parse perl...
**phix.py** — class: PhixLexer; 10 imports; module: phix
**php.py** — class: PhpLexer, PsyshConsoleLexer, ZephirLexer; 25 imports; method: PhpLexer.__init__, PhpLexer.analyse_text, PhpLexer.get_tokens_unprocessed, PsyshConsoleLexer.__init__, PsyshConsoleLexer.get_tokens_unprocessed; module: php
**pointless.py** — class: PointlessLexer; 11 imports; module: pointless
**pony.py** — class: PonyLexer; 11 imports; module: pony
**praat.py** — class: PraatLexer; 13 imports; module: praat
**procfile.py** — class: ProcfileLexer; 7 imports; module: procfile
**prolog.py** — class: LogtalkLexer, PrologLexer; 11 imports; method: LogtalkLexer.analyse_text, PrologLexer.analyse_text; module: prolog
**promql.py** — class: PromQLLexer; 12 imports; module: promql
**prql.py** — class: PrqlLexer; 15 imports; method: PrqlLexer.fstring_rules, PrqlLexer.innerstring_rules; module: prql
**ptx.py** — class: PtxLexer; 11 imports; module: ptx
**python.py** — class: CythonLexer, DgLexer, NumPyLexer, Python2Lexer, Python2TracebackLexer, PythonConsoleLexer; 25 imports; method: NumPyLexer.analyse_text, NumPyLexer.get_tokens_unprocessed, Python2Lexer.analyse_text, Python2Lexer.innerstring_rules, PythonConsoleLexer.__init__, PythonLexer.analyse_text; module: python
**q.py** — class: KLexer, QLexer; 14 imports; module: q
**qlik.py** — class: QlikLexer; 17 imports; module: qlik
**qvt.py** — class: QVToLexer; 14 imports; module: qvt
**r.py** — class: RConsoleLexer, RdLexer, SLexer; 15 imports; method: RConsoleLexer.get_tokens_unprocessed, SLexer.analyse_text; module: r
**rdf.py** — class: ShExCLexer, SparqlLexer, TurtleLexer; 15 imports; method: TurtleLexer.analyse_text; module: rdf
**rebol.py** — class: RebolLexer, RedLexer; 12 imports; method: RebolLexer.analyse_text, RebolLexer.word_callback, RedLexer.word_callback; module: rebol
**rego.py** — class: RegoLexer; 10 imports; module: rego
**rell.py** — class: RellLexer; 11 imports; module: rell
**resource.py** — class: ResourceLexer; 11 imports; method: ResourceLexer.analyse_text; module: resource
**ride.py** — class: RideLexer; 10 imports; module: ride
**rita.py** — class: RitaLexer; 8 imports; module: rita
**rnc.py** — class: RNCCompactLexer; 8 imports; module: rnc
**roboconf.py** — class: RoboconfGraphLexer, RoboconfInstancesLexer; 8 imports; module: roboconf
**robotframework.py** — class: Comment, ForLoop, GherkinTokenizer, ImportSetting, KeywordCall, KeywordSetting; function: normalize; 3 imports; method: ForLoop.__init__, ForLoop._tokenize, GherkinTokenizer.tokenize, KeywordCall.__init__, KeywordCall._tokenize, KeywordTable._is_template; module: robotframework
**ruby.py** — class: FancyLexer, RubyConsoleLexer, RubyLexer; 23 imports; method: RubyConsoleLexer.get_tokens_unprocessed, RubyLexer.analyse_text, RubyLexer.gen_rubystrings_rules, RubyLexer.heredoc_callback; module: ruby
**rust.py** — class: RustLexer; 14 imports; module: rust
**sas.py** — class: SASLexer; 12 imports; module: sas
**savi.py** — class: SaviLexer; 13 imports; module: savi
**scdoc.py** — class: ScdocLexer; 11 imports; method: ScdocLexer.analyse_text; module: scdoc
**scripting.py** — class: AppleScriptLexer, ChaiscriptLexer, EasytrieveLexer, HybrisLexer, JclLexer, LSLLexer; function: _luau_make_expression, _luau_make_expression_special, all_lua_builtins; 23 imports; method: EasytrieveLexer.analyse_text, HybrisLexer.analyse_text, JclLexer.analyse_text, LuaLexer.__init__, LuaLexer.get_tokens_unprocessed, LuauLexer.__init__; module: scripting; rationale: [NOTE] PARAM is not a proper English word, so this is, [NOTE] We cannot use r'\b' at the start and end of keywords because, [TODO] JES3 statement, [XXX] use words() for all of these
**sgf.py** — class: SmartGameFormatLexer; 7 imports; module: sgf
**shell.py** — class: BashLexer, BashSessionLexer, BatchLexer, ExeclineLexer, FishShellLexer, MSDOSSessionLexer; 22 imports; method: BashLexer.analyse_text, BatchLexer._make_arithmetic_state, BatchLexer._make_begin_state, BatchLexer._make_call_state, BatchLexer._make_follow_state, BatchLexer._make_label_state; module: shell
**sieve.py** — class: SieveLexer; 9 imports; module: sieve
**slash.py** — class: SlashLanguageLexer, SlashLexer; 13 imports; method: SlashLanguageLexer.move_state, SlashLanguageLexer.right_angle_bracket, SlashLexer.__init__; module: slash
**smalltalk.py** — class: NewspeakLexer, SmalltalkLexer; 12 imports; module: smalltalk
**smithy.py** — class: SmithyLexer; 11 imports; module: smithy
**smv.py** — class: NuSMVLexer; 9 imports; module: smv
**snobol.py** — class: SnobolLexer; 10 imports; module: snobol
**solidity.py** — class: SolidityLexer; 13 imports; module: solidity
**soong.py** — class: SoongLexer; 10 imports; module: soong
**sophia.py** — class: SophiaLexer; 12 imports; module: sophia
**special.py** — class: OutputLexer, RawTokenLexer, TextLexer; 10 imports; method: OutputLexer.get_tokens_unprocessed, RawTokenLexer.__init__, RawTokenLexer.get_tokens, RawTokenLexer.get_tokens_unprocessed, TextLexer.analyse_text, TextLexer.get_tokens_unprocessed; module: special
**spice.py** — class: SpiceLexer; 12 imports; module: spice
**sql.py** — class: GoogleSqlLexer, MySqlLexer, PlPgsqlLexer, PostgresBase, PostgresConsoleLexer, PostgresExplainLexer; function: language_callback; 25 imports; method: GoogleSqlLexer.analyse_text, MySqlLexer.analyse_text, PostgresBase._get_lexer, PostgresBase.get_tokens_unprocessed, PostgresConsoleLexer.get_tokens_unprocessed, SqlLexer.analyse_text; module: sql; rationale: [FIXME] use inheritance, [NOTE] Although the first regex supports unquoted all-numeric, [NOTE] Although the first regex supports unquoted all-numeric, [TODO] Backslash escapes?, [TODO] better handle multiline comments at the end with, [TODO] better logging
**srcinfo.py** — class: SrcinfoLexer; 8 imports; module: srcinfo
**stata.py** — class: StataLexer; 14 imports; module: stata
**supercollider.py** — class: SuperColliderLexer; 13 imports; method: SuperColliderLexer.analyse_text; module: supercollider
**tablegen.py** — class: TableGenLexer; 15 imports; module: tablegen; rationale: [NOTE] Must escape (pop Cpplexer) codeblock to avoid infinite loop.
**tact.py** — class: TactLexer; 12 imports; module: tact
**tal.py** — class: TalLexer; 10 imports; method: TalLexer.analyse_text; module: tal
**tcl.py** — class: TclLexer; 12 imports; method: TclLexer._gen_command_rules, TclLexer.analyse_text; module: tcl; rationale: [HACK] somehow we miscounted our braces
**teal.py** — class: TealLexer; 11 imports; module: teal
**templates.py** — class: Angular2HtmlLexer, Angular2Lexer, CheetahHtmlLexer, CheetahJavascriptLexer, CheetahLexer, CheetahPythonLexer; 37 imports; method: Angular2HtmlLexer.__init__, CheetahHtmlLexer.__init__, CheetahJavascriptLexer.__init__, CheetahPythonLexer.get_tokens_unprocessed, CheetahXmlLexer.__init__, ColdfusionCFCLexer.__init__; module: templates; rationale: [FIXME] I want to make these keywords but still parse attributes., [NOTE] '\w\W' != '.' without DOTALL., [NOTE] '\w\W' != '.' without DOTALL.
**teraterm.py** — class: TeraTermLexer; 12 imports; method: TeraTermLexer.analyse_text; module: teraterm
**testing.py** — class: GherkinLexer, TAPLexer; 10 imports; method: GherkinLexer.analyse_text; module: testing
**text.py** — 29 imports; module: text
**textedit.py** — class: AwkLexer, SedLexer, VimLexer; 21 imports; method: VimLexer.__init__, VimLexer.get_tokens_unprocessed, VimLexer.is_in; module: textedit; rationale: [TODO] builtins are only subsequent tokens on lines, [TODO] regexes can have other delims
**textfmts.py** — class: GettextLexer, HttpLexer, IrcLogsLexer, KernelLogLexer, NotmuchLexer, TodotxtLexer; 19 imports; method: HttpLexer.analyse_text, HttpLexer.content_callback, HttpLexer.continuous_header_callback, HttpLexer.get_tokens_unprocessed, HttpLexer.header_callback, NotmuchLexer.__init__; module: textfmts; rationale: [TODO] Make date regex more ISO 8601 compliant
**theorem.py** — class: IsabelleLexer, RocqLexer; 15 imports; method: RocqLexer.analyse_text; module: theorem
**thingsdb.py** — class: ThingsDBLexer; 12 imports; module: thingsdb
**tlb.py** — class: TlbLexer; 9 imports; module: tlb
**tls.py** — class: TlsLexer; 11 imports; module: tls
**tnt.py** — class: TNTLexer; 10 imports; method: TNTLexer.__init__, TNTLexer.error_till_line_end, TNTLexer.formula, TNTLexer.get_tokens_unprocessed, TNTLexer.lineno, TNTLexer.rule; module: tnt
**trafficscript.py** — class: RtsLexer; 8 imports; module: trafficscript
**typoscript.py** — class: TypoScriptCssDataLexer, TypoScriptHtmlDataLexer, TypoScriptLexer; 12 imports; module: typoscript
**typst.py** — class: TypstLexer; 15 imports; method: TypstLexer.__init__, TypstLexer.get_tokens_unprocessed; module: typst; rationale: [FIXME] make this work
**ul4.py** — class: CSSUL4Lexer, HTMLUL4Lexer, JavascriptUL4Lexer, PythonUL4Lexer, UL4Lexer, XMLUL4Lexer; 20 imports; method: CSSUL4Lexer.__init__, HTMLUL4Lexer.__init__, JavascriptUL4Lexer.__init__, PythonUL4Lexer.__init__, XMLUL4Lexer.__init__; module: ul4
**unicon.py** — class: IconLexer, UcodeLexer, UniconLexer; 15 imports; method: UcodeLexer.analyse_text; module: unicon
**urbi.py** — class: UrbiscriptLexer; 11 imports; method: UrbiscriptLexer.analyse_text, UrbiscriptLexer.blob_callback; module: urbi
**usd.py** — class: UsdLexer; function: _keywords; 17 imports; module: usd
**varnish.py** — class: VCLLexer, VCLSnippetLexer; 17 imports; method: VCLLexer.analyse_text, VCLSnippetLexer.analyse_text; module: varnish
**verification.py** — class: BoogieLexer, SilverLexer; 11 imports; module: verification
**verifpal.py** — class: VerifpalLexer; 10 imports; module: verifpal
**vip.py** — class: VisualPrologBaseLexer, VisualPrologGrammarLexer, VisualPrologLexer; 14 imports; method: VisualPrologGrammarLexer.analyse_text, VisualPrologLexer.analyse_text; module: vip
**vyper.py** — class: VyperLexer; 12 imports; module: vyper
**web.py** — 26 imports; module: web
**webassembly.py** — class: WatLexer; 12 imports; module: webassembly
**webidl.py** — class: WebIDLLexer; 11 imports; module: webidl
**webmisc.py** — class: CirruLexer, DuelLexer, QmlLexer, SlimLexer, XQueryLexer; 22 imports; method: XQueryLexer.operator_root_callback, XQueryLexer.popstate_callback, XQueryLexer.popstate_kindtest_callback, XQueryLexer.popstate_tag_callback, XQueryLexer.popstate_xmlcomment_callback, XQueryLexer.punctuation_root_callback; module: webmisc
**wgsl.py** — class: WgslLexer; 12 imports; module: wgsl; rationale: [TODO] Treat context-depedendent names specially, [TODO] templates start and end tokens.
**whiley.py** — class: WhileyLexer; 11 imports; module: whiley
**wowtoc.py** — class: WoWTocLexer; function: _create_tag_line_pattern, _create_tag_line_token; 9 imports; method: WoWTocLexer.analyse_text; module: wowtoc
**wren.py** — class: WrenLexer; 12 imports; module: wren
**x10.py** — class: X10Lexer; 5 imports; module: x10
**xorg.py** — class: XorgLexer; 6 imports; module: xorg
**yang.py** — class: YangLexer; 9 imports; module: yang
**yara.py** — class: YaraLexer; 11 imports; module: yara
**zig.py** — class: ZigLexer; 10 imports; module: zig
**modeline.py** — function: get_filetype_from_buffer, get_filetype_from_line; 1 imports; module: modeline
**plugin.py** — function: find_plugin_filters, find_plugin_formatters, find_plugin_lexers, find_plugin_styles, iter_entry_points; 2 imports; module: plugin
**regexopt.py** — function: commonprefix, make_charset, regex_opt, regex_opt_inner; 4 imports; module: regexopt
**scanner.py** — class: EndOfText, Scanner; 1 imports; method: Scanner.__init__, Scanner.__repr__, Scanner.check, Scanner.eos, Scanner.get_char, Scanner.scan; module: scanner
**sphinxext.py** — class: PygmentsDoc; function: setup; 12 imports; method: PygmentsDoc.document_filters, PygmentsDoc.document_formatters, PygmentsDoc.document_lexers, PygmentsDoc.document_lexers_overview, PygmentsDoc.run; module: sphinxext
**style.py** — class: Style, StyleMeta; 2 imports; method: StyleMeta.__iter__, StyleMeta.__len__, StyleMeta.__new__, StyleMeta.list_styles, StyleMeta.style_for_token, StyleMeta.styles_token; module: style
**__init__.py** — function: get_all_styles, get_style_by_name; 3 imports; module: __init__
**_mapping.py** — module: _mapping
**abap.py** — class: AbapStyle; 8 imports; module: abap
**algol.py** — class: AlgolStyle; 7 imports; module: algol
**algol_nu.py** — class: Algol_NuStyle; 7 imports; module: algol_nu
**arduino.py** — class: ArduinoStyle; 10 imports; module: arduino
**autumn.py** — class: AutumnStyle; 10 imports; module: autumn
**borland.py** — class: BorlandStyle; 10 imports; module: borland
**bw.py** — class: BlackWhiteStyle; 8 imports; module: bw
**coffee.py** — class: CoffeeStyle; 12 imports; module: coffee
**colorful.py** — class: ColorfulStyle; 10 imports; module: colorful
**default.py** — class: DefaultStyle; 10 imports; module: default
**dracula.py** — class: DraculaStyle; 14 imports; module: dracula
**emacs.py** — class: EmacsStyle; 10 imports; module: emacs
**friendly.py** — class: FriendlyStyle; 10 imports; module: friendly
**friendly_grayscale.py** — class: FriendlyGrayscaleStyle; 10 imports; module: friendly_grayscale
**fruity.py** — class: FruityStyle; 9 imports; module: fruity
**gh_dark.py** — class: GhDarkStyle; 12 imports; module: gh_dark
**gruvbox.py** — class: GruvboxDarkStyle, GruvboxLightStyle; 10 imports; module: gruvbox
**igor.py** — class: IgorStyle; 5 imports; module: igor
**inkpot.py** — class: InkPotStyle; 13 imports; module: inkpot
**lightbulb.py** — class: LightbulbStyle; 12 imports; module: lightbulb
**lilypond.py** — class: LilyPondStyle; 2 imports; module: lilypond
**lovelace.py** — class: LovelaceStyle; 11 imports; module: lovelace
**manni.py** — class: ManniStyle; 10 imports; module: manni
**material.py** — class: MaterialStyle; 13 imports; module: material
**monokai.py** — class: MonokaiStyle; 14 imports; module: monokai
**murphy.py** — class: MurphyStyle; 10 imports; module: murphy
**native.py** — class: NativeStyle; 11 imports; module: native
**nord.py** — class: NordDarkerStyle, NordStyle; 13 imports; module: nord
**onedark.py** — class: OneDarkStyle; 10 imports; module: onedark
**paraiso_dark.py** — class: ParaisoDarkStyle; 14 imports; module: paraiso_dark
**paraiso_light.py** — class: ParaisoLightStyle; 14 imports; module: paraiso_light
**pastie.py** — class: PastieStyle; 10 imports; module: pastie
**perldoc.py** — class: PerldocStyle; 10 imports; module: perldoc
**rainbow_dash.py** — class: RainbowDashStyle; 11 imports; module: rainbow_dash
**rrt.py** — class: RrtStyle; 9 imports; module: rrt
**sas.py** — class: SasStyle; 10 imports; module: sas
**solarized.py** — class: SolarizedDarkStyle, SolarizedLightStyle; function: make_style; 10 imports; module: solarized
**staroffice.py** — class: StarofficeStyle; 6 imports; module: staroffice
**stata_dark.py** — class: StataDarkStyle; 11 imports; module: stata_dark
**stata_light.py** — class: StataLightStyle; 10 imports; module: stata_light
**tango.py** — class: TangoStyle; 13 imports; module: tango
**trac.py** — class: TracStyle; 10 imports; module: trac
**vim.py** — class: VimStyle; 11 imports; module: vim
**vs.py** — class: VisualStudioStyle; 8 imports; module: vs
**xcode.py** — class: XcodeStyle; 9 imports; module: xcode
**zenburn.py** — class: ZenburnStyle; 12 imports; module: zenburn
**token.py** — class: _TokenType; function: is_token_subtype, string_to_tokentype; method: _TokenType.__contains__, _TokenType.__copy__, _TokenType.__deepcopy__, _TokenType.__getattr__, _TokenType.__init__, _TokenType.__repr__; module: token
**unistring.py** — function: _handle_runs, allexcept, combine; 1 imports; module: unistring
**util.py** — class: ClassNotFound, Future, OptionError, UnclosingTextIOWrapper; function: docstring_headline, doctype_matches, duplicates_removed, format_lines, get_bool_opt, get_choice_opt; 3 imports; method: Future.get, UnclosingTextIOWrapper.close; module: util
**__init__.py** — 7 imports; module: __init__
**decoders.py** — class: Base64Decoder, QuotedPrintableDecoder; 6 imports; method: Base64Decoder.__init__, Base64Decoder.__repr__, Base64Decoder.close, Base64Decoder.finalize, Base64Decoder.write, QuotedPrintableDecoder.__init__; module: decoders
**exceptions.py** — class: DecodeError, FileError, FormParserError, MultipartParseError, ParseError, QuerystringParseError; method: ParseError.__init__; module: exceptions
**multipart.py** — class: BaseParser, Field, File, FormParser, MultipartParser, MultipartState; function: _parseparam, create_form_parser, parse_form, parse_options_header; 24 imports; method: BaseParser.__init__, BaseParser.__repr__, BaseParser.callback, BaseParser.close, BaseParser.finalize, BaseParser.set_callback; module: multipart; rationale: [TODO] check for error here., [TODO] check that we properly handle 8bit / 7bit encoding., [TODO] check the parser's return value for errors?, [TODO] verify that we're in the state MultipartState.END, otherwise throw an, [TODO] what happens if we don't have a filename?
**pythoncom.py** — function: __getattr__; 4 imports; module: pythoncom
**basictimerapp.py** — class: EachAnyIntervaler, EachDayIntervaler, EachHourIntervaler, EachMinuteIntervaler, TimerAppDialog, TimerDialogApp; function: DoDemoWork, t; 8 imports; method: EachAnyIntervaler.SetFirstTime, EachAnyIntervaler.SetNextTime, EachAnyIntervaler.__init__, EachDayIntervaler.__init__, EachHourIntervaler.__init__, EachMinuteIntervaler.__init__; module: basictimerapp
**customprint.py** — class: ImagePrintDialog, PrintDemoApp, PrintDemoTemplate, PrintDemoView; 6 imports; method: ImagePrintDialog.OnInitDialog, ImagePrintDialog.OnOK, ImagePrintDialog.__init__, PrintDemoApp.InitInstance, PrintDemoApp.__init__, PrintDemoTemplate._SetupSharedMenu_; module: customprint
**demoutils.py** — function: NeedApp, NeedGoodGUI, NotAScript; 5 imports; module: demoutils
**dlgappdemo.py** — class: TestAppDialog, TestDialogApp; 4 imports; method: TestAppDialog.OnInitDialog, TestAppDialog.PreDoModal, TestAppDialog.__init__, TestAppDialog.write, TestDialogApp.CreateDialog; module: dlgappdemo; rationale: [NOTE] You CAN NOT import this module from either PythonWin or Python.
**dojobapp.py** — class: CopyToDialogApp, DoJobAppDialog, DoJobDialogApp; function: t; 4 imports; method: CopyToDialogApp.__init__, DoJobAppDialog.OnDestroy, DoJobAppDialog.OnInitDialog, DoJobAppDialog.PreDoModal, DoJobAppDialog.ProcessArgs, DoJobAppDialog.__init__; module: dojobapp
**helloapp.py** — class: HelloApp, HelloWindow; 4 imports; method: HelloApp.InitInstance, HelloWindow.__init__; module: helloapp
**cmdserver.py** — class: ThreadWriter, flags; function: ServerThread, StartServer, Test; 7 imports; method: ThreadWriter.__init__, ThreadWriter.getwriter, ThreadWriter.register, ThreadWriter.unregister, ThreadWriter.write; module: cmdserver
**createwin.py** — class: Control, RedBox, RedBoxWithPie, TestDialog, TestPieDialog; function: MakeDlgTemplate, demo; 5 imports; method: Control.DoPaint, Control.OnPaint, Control.__init__, RedBox.DoPaint, RedBoxWithPie.DoPaint, TestDialog.OnInitDialog; module: createwin
**demoutils.py** — function: NeedApp, NeedGoodGUI, NotAScript; 6 imports; module: demoutils
**dibdemo.py** — class: DIBDemo, DIBView; 4 imports; method: DIBDemo.OnCreateClient, DIBDemo.__init__, DIBView.OnDraw, DIBView.OnSize, DIBView.__init__; module: dibdemo
**dlgtest.py** — class: TestDialog, TestPage, TestSheet; function: d, demo, test; 7 imports; method: TestDialog.KillFocus, TestDialog.OnDestroy, TestDialog.OnInitDialog, TestDialog.OnNotify, TestDialog.__init__, TestPage.OnInitDialog; module: dlgtest
**dyndlg.py** — function: MakeDlgTemplate, test1, test2, test3, test4, testall; 3 imports; module: dyndlg
**fontdemo.py** — class: FontView; function: FontDemo; 5 imports; method: FontView.OnAttachedObjectDeath, FontView.OnDraw, FontView.OnPrepareDC, FontView.OnSize, FontView.SetFont, FontView.__init__; module: fontdemo
**guidemo.py** — function: _exec_demo, demo; 4 imports; module: guidemo
**hiertest.py** — class: DirHierList, HLIFileDir, HierListFrame, HierListView, TestDocument; function: GetTestRoot, demo, demoboth, demodlg, demohli, demomodeless; 7 imports; method: DirHierList.GetSelectedBitmapColumn, DirHierList.GetSubList, DirHierList.GetText, DirHierList.IsExpandable, DirHierList.__init__, HLIFileDir.GetSubList; module: hiertest
**menutest.py** — 3 imports; module: menutest
**objdoc.py** — class: object_document, object_template, object_view; function: demo; 3 imports; method: object_document.OnOpenDocument, object_document.__init__, object_template.OpenObject, object_template.__init__, object_view.OnInitialUpdate; module: objdoc
**demoutils.py** — function: NeedApp, NeedGoodGUI, NotAScript; 5 imports; module: demoutils
**flash.py** — class: BrowserFrame, MyFlashComponent; function: Demo; 8 imports; method: BrowserFrame.Create, BrowserFrame.OnSize, BrowserFrame.__init__, MyFlashComponent.OnFSCommand, MyFlashComponent.OnProgress, MyFlashComponent.OnReadyStateChange; module: flash
**msoffice.py** — class: ExcelView, OleClientItem, OleDocument, OleTemplate, WordFrame; function: Demo; 10 imports; method: ExcelView.EmbedExcel, ExcelView.OnDraw, ExcelView.OnInitialUpdate, ExcelView.OnSetFocus, ExcelView.OnSize, OleClientItem.OnActivate; module: msoffice; rationale: [TODO] update any cache you may have of the item's rectangle/extent
**ocxserialtest.py** — class: MySerialControl, TestSerDialog; function: MakeDlgTemplate, test; 7 imports; method: MySerialControl.OnComm, MySerialControl.__init__, TestSerDialog.OnComm, TestSerDialog.OnDestroy, TestSerDialog.OnInitDialog, TestSerDialog.OnKey; module: ocxserialtest
**ocxtest.py** — class: OCXFrame; function: GetTestCalendarClass, GetTestVideoDialogClass, GetTestVideoModule, MDITest, MakeDlgTemplate, demo; 10 imports; method: OCXFrame.Create, OCXFrame.__init__; module: ocxtest
**webbrowser.py** — class: BrowserFrame, MyWebBrowser; function: Demo; 8 imports; method: BrowserFrame.Create, BrowserFrame.OnNavigate, BrowserFrame.OnSize, BrowserFrame.__init__, MyWebBrowser.OnBeforeNavigate2; module: webbrowser
**openGLDemo.py** — class: CubeView, OpenGLView, TestView; function: ComponentFromIndex, test; 48 imports; method: CubeView.DrawScene, CubeView.Init, CubeView.OnSizeChange, CubeView.OnTimer, CubeView.Term, OpenGLView.DrawScene; module: openGLDemo
**progressbar.py** — class: TestDialog; function: MakeDlgTemplate, demo; 3 imports; method: TestDialog.OnInitDialog, TestDialog.OnOK; module: progressbar
**sliderdemo.py** — class: MyDialog; function: demo; 3 imports; method: MyDialog.OnCancel, MyDialog.OnInitDialog, MyDialog.OnSliderMove, MyDialog.__init__; module: sliderdemo
**splittst.py** — class: SampleTemplate, SplitterFrame; function: demo; 6 imports; method: SampleTemplate.InitialUpdateFrame, SampleTemplate.__init__, SplitterFrame.InitialUpdateFrame, SplitterFrame.OnCreateClient, SplitterFrame.OnDestroy, SplitterFrame.__init__; module: splittst
**threadedgui.py** — class: FontFrame, FontWindow, TestThread, ThreadedFontFrame; function: Demo, ThreadedDemo; 7 imports; method: FontFrame.Create, FontFrame.__init__, FontWindow.ChangeAttributes, FontWindow.Create, FontWindow.OnDestroy, FontWindow.OnPaint; module: threadedgui
**toolbar.py** — class: GenericFrame; function: test; 7 imports; method: GenericFrame.GetMessageString, GenericFrame.GetTTText, GenericFrame.OnCreateClient, GenericFrame.OnDestroy, GenericFrame.OnNext, GenericFrame.OnPrevious; module: toolbar
**__init__.py** — module: __init__
**__init__.py** — function: GetDebugger, _CheckNeedGUI, _GetCurrentDebugger, close, pm, post_mortem; 6 imports; module: __init__
**configui.py** — class: DebuggerOptionsPropPage; 4 imports; method: DebuggerOptionsPropPage.OnInitDialog, DebuggerOptionsPropPage.OnOK, DebuggerOptionsPropPage.__init__; module: configui
**dbgcon.py** — function: DoGetOption, LoadDebuggerOptions, SaveDebuggerOptions; 1 imports; module: dbgcon
**dbgpyapp.py** — class: DebuggerPythonApp; 5 imports; method: DebuggerPythonApp.InitInstance, DebuggerPythonApp.LoadMainFrame; module: dbgpyapp
**debugger.py** — class: Debugger, DebuggerBreakpointsWindow, DebuggerListViewWindow, DebuggerStackWindow, DebuggerWatchWindow, DebuggerWindow; function: CreateDebuggerDialog, PrepareControlBars, SetInteractiveContext, _LineStateToMarker; 26 imports; method: Debugger.GUIAboutToBreak, Debugger.GUIAboutToFinishInteract, Debugger.GUIAboutToInteract, Debugger.GUIAboutToRun, Debugger.GUICheckInit, Debugger.GUIRespondDebuggerData; module: debugger
**fail.py** — function: a, b, c, d, e; 3 imports; module: fail
**ideoptions.py** — class: OptionsPropPage; 4 imports; method: OptionsPropPage.ChangeFormat, OptionsPropPage.HandleCharFormatChange, OptionsPropPage.OnFormatError, OptionsPropPage.OnFormatInput, OptionsPropPage.OnFormatOutput, OptionsPropPage.OnFormatTitle; module: ideoptions
**list.py** — class: ListDialog, ListsDialog; function: SelectFromList, SelectFromLists, test; 5 imports; method: ListDialog.FillList, ListDialog.LayoutControls, ListDialog.OnInitDialog, ListDialog.OnListClick, ListDialog.OnListItemChange, ListDialog.__init__; module: list
**login.py** — class: LoginDlg, PasswordDlg; function: GetLogin, GetPassword, MakeLoginDlgTemplate, MakePasswordDlgTemplate; 4 imports; method: LoginDlg.__init__, PasswordDlg.__init__; module: login
**status.py** — class: CStatusProgressDialog, CThreadedStatusProcessDialog, ProgressThread; function: MakeProgressDlgTemplate, StatusProgressDialog, ThreadedStatusProgressDialog, demo, thread_demo; 7 imports; method: CStatusProgressDialog.Close, CStatusProgressDialog.OnInitDialog, CStatusProgressDialog.Set, CStatusProgressDialog.SetMaxTicks, CStatusProgressDialog.SetText, CStatusProgressDialog.SetTitle; module: status
**DockingBar.py** — class: DockingBar; function: CenterPoint, DeflateRect, EditCreator, OffsetRect, PtInRect, test; 6 imports; method: DockingBar.CalcDynamicLayout, DockingBar.CalcFixedLayout, DockingBar.ClientToWnd, DockingBar.CreateWindow, DockingBar.DrawGripper, DockingBar.HookMessages; module: DockingBar
**app.py** — class: AboutBox, CApp, MainFrame; function: CheckCreateDefaultGUI, CreateDefaultGUI, HaveGoodGUI, HookInput, LoadWindowSize, RectToCreateStructRect; 19 imports; method: AboutBox.OnButHomePage, AboutBox.OnInitDialog, AboutBox.__init__, CApp.AddIdleHandler, CApp.CreateMainFrame, CApp.DeleteIdleHandler; module: app
**bitmap.py** — class: BitmapDocument, BitmapFrame, BitmapTemplate, BitmapView; function: demo, t; 8 imports; method: BitmapDocument.DeleteContents, BitmapDocument.OnNewDocument, BitmapDocument.OnOpenDocument, BitmapDocument.__init__, BitmapFrame.OnCreateClient, BitmapTemplate.MatchDocType; module: bitmap
**cmdline.py** — function: FixArgFileName, ParseArgs; 4 imports; module: cmdline
**dbgcommands.py** — class: DebuggerCommandHandler; 7 imports; method: DebuggerCommandHandler.HookCommands, DebuggerCommandHandler.OnAdd, DebuggerCommandHandler.OnClearAll, DebuggerCommandHandler.OnClose, DebuggerCommandHandler.OnDebuggerBar, DebuggerCommandHandler.OnDebuggerToolbar; module: dbgcommands
**dlgappcore.py** — class: AppDialog, DialogApp; 5 imports; method: AppDialog.OnEraseBkgnd, AppDialog.OnInitDialog, AppDialog.OnPaint, AppDialog.OnQueryDragIcon, AppDialog.PreDoModal, AppDialog.__init__; module: dlgappcore
**ModuleBrowser.py** — class: BrowserView, HierListCLBRClass, HierListCLBRErrorItem, HierListCLBRErrorRoot, HierListCLBRFunction, HierListCLBRItem; 9 imports; method: BrowserView.CheckMadeList, BrowserView.CheckRefreshList, BrowserView.DestroyBrowser, BrowserView.DestroyList, BrowserView.OnActivateView, BrowserView.OnInitialUpdate; module: ModuleBrowser
**__init__.py** — function: DeleteEditorOption, GetEditorFontOption, GetEditorOption, LoadDefaultEditor, SetEditorFontOption, SetEditorOption; 2 imports; module: __init__
**coloreditor.py** — class: SplitterFrame, SyntEditDocument, SyntEditTemplate, SyntEditView; 16 imports; method: SplitterFrame.OnCreate, SplitterFrame.OnWindowSplit, SyntEditDocument.FinalizeViewCreation, SyntEditDocument.HookViewNotifications, SyntEditDocument.OnDebuggerStateChange, SyntEditTemplate.CheckIDLEMenus; module: coloreditor
**configui.py** — class: EditorPropertyPage, EditorWhitespacePropertyPage; function: testpp; 11 imports; method: EditorPropertyPage.OnButEdgeColor, EditorPropertyPage.OnButSimple, EditorPropertyPage.OnInitDialog, EditorPropertyPage.OnOK, EditorPropertyPage.UpdateUIForState, EditorPropertyPage._AddEditorOption; module: configui
**document.py** — class: EditorDocumentBase, FileWatchingThread; 11 imports; method: EditorDocumentBase.CheckExternalDocumentUpdated, EditorDocumentBase.CheckMakeDocumentWritable, EditorDocumentBase.FinalizeViewCreation, EditorDocumentBase.HookViewNotifications, EditorDocumentBase.MakeDocumentWritable, EditorDocumentBase.OnCloseDocument; module: document
**editor.py** — class: EditorDocument, EditorTemplate, EditorView; function: Create; 14 imports; method: EditorDocument.OnOpenDocument, EditorDocument.SaveFile, EditorDocument.SetAllLineColors, EditorDocument.SetLineColor, EditorDocument.TranslateLoadedData, EditorTemplate.CreateWin32uiDocument; module: editor
**frame.py** — class: EditorFrame; 4 imports; method: EditorFrame.GetBrowserView, EditorFrame.GetEditorView, EditorFrame.OnClose, EditorFrame.OnCreateClient; module: frame
**template.py** — class: EditorTemplateBase; 6 imports; method: EditorTemplateBase.CreateWin32uiDocument, EditorTemplateBase.GetFileExtensions, EditorTemplateBase.GetPythonPropertyPages, EditorTemplateBase.InitialUpdateFrame, EditorTemplateBase.MatchDocType, EditorTemplateBase.OpenDocumentFile; module: template
**vss.py** — function: CheckoutFile, FindVssProjectInfo; 8 imports; module: vss
**help.py** — function: FinalizeHelp, HandleHelpOtherCommand, ListAllHelpFiles, OpenHelpFile, SelectAndRunHelpFile, SetHelpMenuOtherHelp; 8 imports; module: help
**interact.py** — class: CDockedInteractivePython, CInteractivePython, DockedInteractiveView, InteractiveCore, InteractiveFormatter, InteractiveFrame; function: CloseInteractiveWindow, CreateDockedInteractiveWindow, CreateInteractiveWindow, CreateInteractiveWindowUserPreference, CreateMDIInteractiveWindow, DestroyInteractiveWindow; 19 imports; method: CDockedInteractivePython.Create, CDockedInteractivePython.NeedRecreateWindow, CDockedInteractivePython.RecreateWindow, CDockedInteractivePython.__init__, CInteractivePython.Close, CInteractivePython.OnViewDestroy; module: interact
**intpyapp.py** — class: InteractivePythonApp, MainFrame; function: _SetupSharedMenu_; 27 imports; method: InteractivePythonApp.Activate, InteractivePythonApp.CreateMainFrame, InteractivePythonApp.DoLoadModules, InteractivePythonApp.ExitInstance, InteractivePythonApp.HookCommands, InteractivePythonApp.InitDDE; module: intpyapp
**intpydde.py** — class: DDEServer, DDESystemTopic; 9 imports; method: DDEServer.CreateSystemTopic, DDEServer.OnCreate, DDEServer.Shutdown, DDEServer.Status, DDEServer.__init__, DDESystemTopic.Exec; module: intpydde
**scriptutils.py** — class: DlgRunScript; function: CheckFile, FindTabNanny, GetActiveEditControl, GetActiveEditorDocument, GetActiveFileName, GetActiveView; 16 imports; method: DlgRunScript.OnBrowse, DlgRunScript.OnInitDialog, DlgRunScript.__init__; module: scriptutils
**sgrepmdi.py** — class: GrepDialog, GrepDocument, GrepFrame, GrepParamsDialog, GrepTemplate, GrepView; function: getsubdirs; 10 imports; method: GrepDialog.OnMoreDirectories, GrepDialog.OnMoreFiles, GrepDialog.OnOK, GrepDialog.__init__, GrepDialog.getMore, GrepDocument.GetParams; module: sgrepmdi
**startup.py** — 7 imports; module: startup
**stdin.py** — class: Stdin; 1 imports; method: Stdin.__extract_from_buffer, Stdin.__get_line, Stdin.__get_lines, Stdin.__getattr__, Stdin.__init__, Stdin.isatty; module: stdin; rationale: [NOTE] Likely to be None
**toolmenu.py** — class: ToolMenuPropPage; function: HandleToolCommand, LoadToolMenuItems, SetToolsMenu, WriteToolMenuItems; 8 imports; method: ToolMenuPropPage.OnButtonDelete, ToolMenuPropPage.OnButtonMove, ToolMenuPropPage.OnButtonNew, ToolMenuPropPage.OnCommandEditControls, ToolMenuPropPage.OnInitDialog, ToolMenuPropPage.OnNotifyListControl; module: toolmenu
**window.py** — class: MDIChildWnd; 2 imports; method: MDIChildWnd.AutoRestore; module: window
**winout.py** — class: WindowOutput, WindowOutputDocument, WindowOutputFrame, WindowOutputViewImpl, WindowOutputViewRTF, WindowOutputViewScintilla; function: RTFWindowOutput, test, thread_test; 14 imports; method: WindowOutput.CheckRecreateWindow, WindowOutput.Close, WindowOutput.Create, WindowOutput.HandleOutput, WindowOutput.HandleSpecialLine, WindowOutput.NeedRecreateWindow; module: winout
**AutoExpand.py** — class: AutoExpand; 2 imports; method: AutoExpand.__init__, AutoExpand.expand_word_event, AutoExpand.getprevword, AutoExpand.getwords; module: AutoExpand
**AutoIndent.py** — class: AutoIndent, IndentSearcher; function: classifyws, index2line; 3 imports; method: AutoIndent.__init__, AutoIndent._asktabwidth, AutoIndent._build_char_in_string_func, AutoIndent._make_blanks, AutoIndent.change_indentwidth_event, AutoIndent.change_tabwidth_event; module: AutoIndent
**CallTips.py** — class: CallTips; function: _find_constructor, get_arg_text; 6 imports; method: CallTips.__init__, CallTips._make_tk_calltip_window, CallTips._remove_calltip_window, CallTips.calltip_cancel_event, CallTips.check_calltip_cancel_event, CallTips.close; module: CallTips
**FormatParagraph.py** — class: FormatParagraph; function: find_paragraph, get_comment_header, get_indent, is_all_white, reformat_paragraph; 1 imports; method: FormatParagraph.__init__, FormatParagraph.close, FormatParagraph.format_paragraph_event; module: FormatParagraph
**IdleHistory.py** — class: History; method: History.__init__, History._get_source, History._put_source, History.history_do, History.history_next, History.history_prev; module: IdleHistory
**PyParse.py** — class: Parser; 2 imports; method: Parser.__init__, Parser._study1, Parser._study2, Parser.compute_backslash_indent, Parser.compute_bracket_indent, Parser.find_good_parse_start; module: PyParse
**__init__.py** — module: __init__
**activex.py** — class: Control; function: MakeControlClass, MakeControlInstance; 3 imports; method: Control.CreateControl, Control.HookOleEvents, Control._GetControlCLSID, Control._GetDispatchClass, Control._GetEventMap, Control.__getattr__; module: activex
**afxres.py** — function: AFX_CONTROLBAR_MASK; module: afxres
**dialog.py** — class: Dialog, PrintDialog, PropertyPage, PropertySheet; function: GetSimpleInput, dllFromDll; 3 imports; method: Dialog.AddDDX, Dialog.HookCommands, Dialog.OnAttachedObjectDeath, Dialog.OnCancel, Dialog.OnDestroy, Dialog.OnInitDialog; module: dialog
**docview.py** — class: CreateContext, CtrlView, DocTemplate, Document, EditView, FormView; function: t; 3 imports; method: CreateContext.__del__, CreateContext.__init__, CreateContext.close, CtrlView.__init__, DocTemplate.CreateCreateContext, DocTemplate.CreateNewDocument; module: docview
**object.py** — class: CmdTarget, Object; 1 imports; method: CmdTarget.HookCommandRange, CmdTarget.HookCommandUpdateRange, CmdTarget.HookNotifyRange, CmdTarget.__init__, Object.OnAttachedObjectDeath, Object.__del__; module: object
**thread.py** — class: WinApp, WinThread; 2 imports; method: WinApp.__init__, WinThread.ExitInstance, WinThread.InitInstance, WinThread.__init__; module: thread
**window.py** — class: FrameWnd, MDIChildWnd, MDIFrameWnd, Wnd; 3 imports; method: FrameWnd.__init__, MDIChildWnd.OnCreateClient, MDIChildWnd.__init__, MDIFrameWnd.__init__, Wnd.OnDestroy, Wnd.__init__; module: window
**IDLEenvironment.py** — class: CallTips, EmptyRange, IDLEEditorWindow, IDLEWrapper, TextError, TkText; function: GetIDLEModule, IDLETest, TestCheck, TestGet, TkIndexToOffset, TkOffsetToIndex; 9 imports; method: CallTips.__init__, CallTips.hidetip, CallTips.showtip, IDLEEditorWindow.GetMenuItems, IDLEEditorWindow.IDLEExtension, IDLEEditorWindow.__init__; module: IDLEenvironment
**__init__.py** — module: __init__
**bindings.py** — class: Binding, BindingsManager, SendCommandHandler; function: assign_command_id; 6 imports; method: Binding.__init__, BindingsManager._OnCommand, BindingsManager.__init__, BindingsManager._get_IDLE_handler, BindingsManager._new_binding, BindingsManager.bind; module: bindings
**config.py** — class: ConfigManager; function: find_config_file, find_config_files, get_section_header, split_line, test; 13 imports; method: ConfigManager.__init__, ConfigManager._load_extensions, ConfigManager._load_general, ConfigManager._load_idle_extensions, ConfigManager._load_keys, ConfigManager._readline; module: config
**configui.py** — class: ScintillaFormatPropertyPage; function: test; 9 imports; method: ScintillaFormatPropertyPage.ApplyUIFormatToStyle, ScintillaFormatPropertyPage.GetSelectedStyle, ScintillaFormatPropertyPage.OnBraceMatch, ScintillaFormatPropertyPage.OnButDefaultFixedFont, ScintillaFormatPropertyPage.OnButDefaultPropFont, ScintillaFormatPropertyPage.OnButFixedOrDefault; module: configui
**control.py** — class: CScintillaColorEditInterface, CScintillaEdit, CScintillaEditInterface, ScintillaControlInterface, ScintillaNotification; 10 imports; method: CScintillaColorEditInterface.ApplyFormattingStyles, CScintillaColorEditInterface.Colorize, CScintillaColorEditInterface.HookFormatter, CScintillaColorEditInterface._GetColorizer, CScintillaColorEditInterface._MakeColorizer, CScintillaEdit.CreateWindow; module: control
**document.py** — class: CScintillaDocument, DocumentNotifyDelegate, ViewNotifyDelegate; 8 imports; method: CScintillaDocument.ApplyFormattingStyles, CScintillaDocument.DeleteContents, CScintillaDocument.FinalizeViewCreation, CScintillaDocument.GetEditorView, CScintillaDocument.HookViewNotifications, CScintillaDocument.MarkerAdd; module: document
**find.py** — class: FindDialog, FindReplaceDialog, ReplaceDialog, SearchParams; function: FindNext, ShowFindDialog, ShowReplaceDialog, _FindIt, _GetControl, _ReplaceIt; 7 imports; method: FindDialog._GetDialogTemplate, FindReplaceDialog.DoFindNext, FindReplaceDialog.OnDestroy, FindReplaceDialog.OnFindNext, FindReplaceDialog.OnInitDialog, FindReplaceDialog.__init__; module: find
**formatter.py** — class: BuiltinPythonSourceFormatter, BuiltinSourceFormatter, Formatter, FormatterBase, PythonSourceFormatter, Style; 11 imports; method: BuiltinPythonSourceFormatter.GetSampleText, BuiltinPythonSourceFormatter.SetStyles, BuiltinPythonSourceFormatter.__init__, BuiltinSourceFormatter.Colorize, BuiltinSourceFormatter.HookFormatter, BuiltinSourceFormatter.RegisterStyle; module: formatter
**keycodes.py** — function: _fillvkmap, _pkn, _psc, get_vk, make_key_name, parse_key_name; 3 imports; module: keycodes; rationale: [NOTE] returning None, None causes an error when keyboard layout is non-English, see th
**scintillacon.py** — module: scintillacon
**view.py** — class: CScintillaView; function: DoBraceMatch, LoadConfiguration, _CreateEvents, _get_class_attributes; 21 imports; method: CScintillaView.AppendMenu, CScintillaView.CalculatePageRanges, CScintillaView.DoConfigChange, CScintillaView.EnsureCharsVisible, CScintillaView.FormatRange, CScintillaView.GetTabWidth; module: view; rationale: [NOTE] Custom print dialogs are stopping the user's values from coming back :-(, [TODO] This is kinda slow. Probably need some kind of cache
**TraceCollector.py** — class: WindowOutput; function: CollectorThread, MakeOutputWindow; 6 imports; method: WindowOutput.Close, WindowOutput._StopThread, WindowOutput.__init__; module: TraceCollector
**browseProjects.py** — class: HLICLBRClass, HLICLBRFunction, HLICLBRItem, HLICLBRMethod, HLIDirectoryItem, HLIErrorItem; function: BrowseDialog, DockableBrowserCreator, DockablePathBrowser, MakePathSubList; 13 imports; method: HLICLBRClass.GetBitmapColumn, HLICLBRClass.GetSubList, HLICLBRClass.IsExpandable, HLICLBRClass.__init__, HLICLBRFunction.GetBitmapColumn, HLICLBRItem.GetText; module: browseProjects
**browser.py** — class: BrowserDocument, BrowserTemplate, BrowserView, DialogShowObject, HLIBuiltinFunction, HLIClass; function: Browse, BrowseMDI, MakeHLI, MakeTemplate, ShowObject; 11 imports; method: BrowserDocument.OnOpenDocument, BrowserDocument.__init__, BrowserTemplate.OpenObject, BrowserTemplate.__init__, BrowserView.OnInitialUpdate, DialogShowObject.OnInitDialog; module: browser
**hierlist.py** — class: HierDialog, HierList, HierListItem, HierListWithItems; function: GetItemText; 8 imports; method: HierDialog.OnInitDialog, HierDialog.__init__, HierList.AcceptRoot, HierList.AddItem, HierList.AddSubList, HierList.CheckChangedChildren; module: hierlist
**regedit.py** — class: HLIRegistryKey, RegDocument, RegTemplate, RegistryTreeView, RegistryValueView, SplitterFrame; function: EditRegistry, SafeApply; 9 imports; method: HLIRegistryKey.GetSubList, HLIRegistryKey.GetText, HLIRegistryKey.IsExpandable, HLIRegistryKey.__eq__, HLIRegistryKey.__init__, HLIRegistryKey.__lt__; module: regedit
**regpy.py** — class: RegEditPropertyPage, RegistryControl, RegistryPage, RegistrySheet; function: t; 3 imports; method: RegEditPropertyPage.GetTemplate, RegistryControl.__init__, RegistryPage.OnInitDialog, RegistryPage.__init__, RegistrySheet.OnActivate, RegistrySheet.__init__; module: regpy
**__init__.py** — 4 imports; module: __init__
**_attrs.py** — class: UnsupportedSubclassing; function: _do_not_subclass, define, frozen; 5 imports; method: UnsupportedSubclassing.__str__; module: _attrs
**_core.py** — class: Anchor, Registry, Resolved, Resolver, Resource, Retrieved; function: _detect_or_default, _detect_or_error, _fail_to_retrieve; 28 imports; method: Anchor.resolve, Registry.__getitem__, Registry.__iter__, Registry.__len__, Registry.__repr__, Registry.__rmatmul__; module: _core; rationale: [TODO] Is this true for non JSON Schema resources? Probably not.
**exceptions.py** — class: CannotDetermineSpecification, InvalidAnchor, NoInternalID, NoSuchAnchor, NoSuchResource, PointerToNowhere; 7 imports; method: CannotDetermineSpecification.__eq__, CannotDetermineSpecification.__hash__, InvalidAnchor.__str__, NoInternalID.__eq__, NoInternalID.__hash__, NoSuchAnchor.__str__; module: exceptions
**jsonschema.py** — class: DynamicAnchor, UnknownDialect; function: _anchor, _anchor_2019, _dollar_id, _legacy_anchor_in_dollar_id, _legacy_anchor_in_id, _legacy_dollar_id; 18 imports; method: DynamicAnchor.resolve; module: jsonschema
**retrieval.py** — function: to_cached_resource; 11 imports; module: retrieval
**test_core.py** — class: TestOpaqueSpecification, TestRegistry, TestResolver, TestResource, TestSpecification; function: blow_up, test_nonsubclassable; 8 imports; method: TestOpaqueSpecification.test_no_anchors, TestOpaqueSpecification.test_no_id, TestOpaqueSpecification.test_no_subresources, TestRegistry.test_anchor_in_nonexistent_resource, TestRegistry.test_bool_empty, TestRegistry.test_bool_not_empty; module: test_core; rationale: [FIXME] The tests below aren't really representable in the current
**test_exceptions.py** — function: pairs, test_eq_incompatible_types, test_hash; 4 imports; module: test_exceptions
**test_jsonschema.py** — function: test_anchors_in_bool, test_empty_registry, test_id_of_bool, test_id_of_mapping, test_lookup_recursive_ref_to_bool, test_lookup_trivial_dynamic_ref; 5 imports; module: test_jsonschema; rationale: [FIXME] The tests below should move to the referencing suite but I haven't yet
**test_referencing_suite.py** — class: SuiteNotFound; function: test_referencing_suite; 7 imports; method: SuiteNotFound.__str__; module: test_referencing_suite
**test_retrieval.py** — class: TestToCachedResource; 8 imports; method: TestToCachedResource.test_custom_cache, TestToCachedResource.test_custom_from_contents, TestToCachedResource.test_custom_loader, TestToCachedResource.test_it_caches_retrieved_resources; module: test_retrieval
**typing.py** — class: Anchor, Retrieve; 10 imports; method: Anchor.name, Anchor.resolve, Retrieve.__call__; module: typing
**__init__.py** — function: get_console, inspect, print, print_json, reconfigure; 11 imports; module: __init__
**__main__.py** — class: ColorBox; function: make_test_card; 19 imports; method: ColorBox.__rich_console__, ColorBox.__rich_measure__; module: __main__
**_emoji_codes.py** — module: _emoji_codes
**_emoji_replace.py** — function: _emoji_replace; 5 imports; module: _emoji_replace
**_export_format.py** — module: _export_format
**_extension.py** — function: load_ipython_extension; 3 imports; module: _extension
**_fileno.py** — function: get_fileno; 3 imports; module: _fileno
**_inspect.py** — class: Inspect; function: _first_paragraph, get_object_types_mro, get_object_types_mro_as_strings, is_object_one_of_types; 24 imports; method: Inspect.__init__, Inspect.__rich__, Inspect._get_formatted_doc, Inspect._get_signature, Inspect._make_title, Inspect._render; module: _inspect
**_log_render.py** — class: LogRender; 15 imports; method: LogRender.__call__, LogRender.__init__; module: _log_render
**_loop.py** — function: loop_first, loop_first_last, loop_last; 3 imports; module: _loop
**_null_file.py** — class: NullFile; 7 imports; method: NullFile.__enter__, NullFile.__exit__, NullFile.__iter__, NullFile.__next__, NullFile.close, NullFile.fileno; module: _null_file
**_palettes.py** — 1 imports; module: _palettes
**_pick.py** — function: pick_bool; 1 imports; module: _pick
**_ratio.py** — class: Edge; function: ratio_distribute, ratio_reduce, ratio_resolve; 8 imports; module: _ratio
**_spinners.py** — module: _spinners
**_stack.py** — class: Stack; 2 imports; method: Stack.push, Stack.top; module: _stack
**_timer.py** — function: timer; 3 imports; module: _timer
**__init__.py** — function: _parse_version, load; 11 imports; module: __init__
**_versions.py** — module: _versions
**unicode10-0-0.py** — 1 imports; module: unicode10-0-0
**unicode11-0-0.py** — 1 imports; module: unicode11-0-0
**unicode12-0-0.py** — 1 imports; module: unicode12-0-0
**unicode12-1-0.py** — 1 imports; module: unicode12-1-0
**unicode13-0-0.py** — 1 imports; module: unicode13-0-0
**unicode14-0-0.py** — 1 imports; module: unicode14-0-0
**unicode15-0-0.py** — 1 imports; module: unicode15-0-0
**unicode15-1-0.py** — 1 imports; module: unicode15-1-0
**unicode16-0-0.py** — 1 imports; module: unicode16-0-0
**unicode17-0-0.py** — 1 imports; module: unicode17-0-0
**unicode4-1-0.py** — 1 imports; module: unicode4-1-0
**unicode5-0-0.py** — 1 imports; module: unicode5-0-0
**unicode5-1-0.py** — 1 imports; module: unicode5-1-0
**unicode5-2-0.py** — 1 imports; module: unicode5-2-0
**unicode6-0-0.py** — 1 imports; module: unicode6-0-0
**unicode6-1-0.py** — 1 imports; module: unicode6-1-0
**unicode6-2-0.py** — 1 imports; module: unicode6-2-0
**unicode6-3-0.py** — 1 imports; module: unicode6-3-0
**unicode7-0-0.py** — 1 imports; module: unicode7-0-0
**unicode8-0-0.py** — 1 imports; module: unicode8-0-0
**unicode9-0-0.py** — 1 imports; module: unicode9-0-0
**_win32_console.py** — class: CONSOLE_CURSOR_INFO, CONSOLE_SCREEN_BUFFER_INFO, LegacyWindowsError, LegacyWindowsTerm, WindowsCoordinates; function: FillConsoleOutputAttribute, FillConsoleOutputCharacter, GetConsoleCursorInfo, GetConsoleMode, GetConsoleScreenBufferInfo, GetStdHandle; 14 imports; method: LegacyWindowsTerm.__init__, LegacyWindowsTerm._get_cursor_size, LegacyWindowsTerm.cursor_position, LegacyWindowsTerm.erase_end_of_line, LegacyWindowsTerm.erase_line, LegacyWindowsTerm.erase_start_of_line; module: _win32_console
**_windows.py** — class: WindowsConsoleFeatures; 10 imports; module: _windows
**_windows_renderer.py** — function: legacy_windows_render; 9 imports; module: _windows_renderer
**_wrap.py** — function: divide_line, words; 7 imports; module: _wrap
**abc.py** — class: RichRenderable; 2 imports; method: RichRenderable.__subclasshook__; module: abc
**align.py** — class: Align, VerticalCenter; 18 imports; method: Align.__init__, Align.__repr__, Align.__rich_console__, Align.__rich_measure__, Align.center, Align.left; module: align
**ansi.py** — class: AnsiDecoder, _AnsiToken; function: _ansi_tokenize; 13 imports; method: AnsiDecoder.__init__, AnsiDecoder.decode, AnsiDecoder.decode_line; module: ansi
**bar.py** — class: Bar; 10 imports; method: Bar.__init__, Bar.__repr__, Bar.__rich_console__, Bar.__rich_measure__; module: bar
**box.py** — class: Box; 12 imports; method: Box.__init__, Box.__repr__, Box.__str__, Box.get_bottom, Box.get_plain_headed_box, Box.get_row; module: box
**cells.py** — class: CellTable; function: _cell_len, _split_text, cached_cell_len, cell_len, chop_cells, get_character_cell_size; 8 imports; module: cells
**color.py** — class: Color, ColorParseError, ColorSystem, ColorType; function: blend_rgb, parse_rgb_hex; 21 imports; method: Color.__rich__, Color.__rich_repr__, Color.default, Color.downgrade, Color.from_ansi, Color.from_rgb; module: color
**color_triplet.py** — class: ColorTriplet; 2 imports; method: ColorTriplet.hex, ColorTriplet.normalized, ColorTriplet.rgb; module: color_triplet
**columns.py** — class: Columns; 22 imports; method: Columns.__init__, Columns.__rich_console__, Columns.add_renderable; module: columns
**console.py** — class: Capture, CaptureError, Console, ConsoleDimensions, ConsoleOptions, ConsoleRenderable; function: _is_jupyter, detect_legacy_windows, get_windows_console_features, group; 89 imports; method: Capture.__enter__, Capture.__exit__, Capture.__init__, Capture.get, Console.__enter__, Console.__exit__; module: console
**constrain.py** — class: Constrain; 8 imports; method: Constrain.__init__, Constrain.__rich_console__, Constrain.__rich_measure__; module: constrain
**containers.py** — class: Lines, Renderables; 18 imports; method: Lines.__getitem__, Lines.__init__, Lines.__iter__, Lines.__len__, Lines.__repr__, Lines.__rich_console__; module: containers
**control.py** — class: Control; function: escape_control_codes, strip_control_codes; 15 imports; method: Control.__init__, Control.__rich_console__, Control.__str__, Control.alt_screen, Control.bell, Control.clear; module: control
**default_styles.py** — 7 imports; module: default_styles
**diagnose.py** — function: report; 7 imports; module: diagnose
**emoji.py** — class: Emoji, NoEmoji; 15 imports; method: Emoji.__init__, Emoji.__repr__, Emoji.__rich_console__, Emoji.__str__, Emoji.replace; module: emoji
**errors.py** — class: ConsoleError, LiveError, MarkupError, MissingStyle, NoAltScreen, NotRenderableError; module: errors
**file_proxy.py** — class: FileProxy; 8 imports; method: FileProxy.__getattr__, FileProxy.__init__, FileProxy.fileno, FileProxy.flush, FileProxy.isatty, FileProxy.rich_proxied_file; module: file_proxy
**filesize.py** — function: _to_str, decimal, pick_unit_and_suffix; 4 imports; module: filesize
**highlighter.py** — class: Highlighter, ISO8601Highlighter, JSONHighlighter, NullHighlighter, RegexHighlighter, ReprHighlighter; function: _combine_regex; 10 imports; method: Highlighter.__call__, Highlighter.highlight, JSONHighlighter.highlight, NullHighlighter.highlight, RegexHighlighter.highlight; module: highlighter
**json.py** — class: JSON; 13 imports; method: JSON.__init__, JSON.__rich__, JSON.from_data; module: json
**jupyter.py** — class: JupyterMixin, JupyterRenderable; function: _render_segments, display, print; 11 imports; method: JupyterMixin._repr_mimebundle_, JupyterRenderable.__init__, JupyterRenderable._repr_mimebundle_; module: jupyter
**layout.py** — class: ColumnSplitter, Layout, LayoutError, LayoutRender, NoSplitter, RowSplitter; 32 imports; method: ColumnSplitter.divide, ColumnSplitter.get_tree_icon, Layout.__getitem__, Layout.__init__, Layout.__rich_console__, Layout.__rich_repr__; module: layout
**live.py** — class: Live, _RefreshThread; 43 imports; method: Live.__enter__, Live.__exit__, Live.__init__, Live._disable_redirect_io, Live._enable_redirect_io, Live.get_renderable; module: live
**live_render.py** — class: LiveRender; 13 imports; method: LiveRender.__init__, LiveRender.__rich_console__, LiveRender.last_render_height, LiveRender.position_cursor, LiveRender.restore_cursor, LiveRender.set_renderable; module: live_render
**logging.py** — class: RichHandler; 25 imports; method: RichHandler.__init__, RichHandler.emit, RichHandler.get_level_text, RichHandler.render, RichHandler.render_message; module: logging
**markdown.py** — class: BlockQuote, CodeBlock, Heading, HeadingFormat, HorizontalRule, ImageItem; 29 imports; method: BlockQuote.__init__, BlockQuote.__rich_console__, BlockQuote.on_child_close, CodeBlock.__init__, CodeBlock.__rich_console__, CodeBlock.create; module: markdown
**markup.py** — class: Tag; function: _parse, escape, render; 19 imports; method: Tag.__str__, Tag.markup; module: markup
**measure.py** — class: Measurement; function: measure_renderables; 12 imports; method: Measurement.clamp, Measurement.get, Measurement.normalize, Measurement.span, Measurement.with_maximum, Measurement.with_minimum; module: measure
**padding.py** — class: Padding; 14 imports; method: Padding.__init__, Padding.__repr__, Padding.__rich_console__, Padding.__rich_measure__, Padding.indent, Padding.unpack; module: padding
**pager.py** — class: Pager, SystemPager; 5 imports; method: Pager.show, SystemPager._pager, SystemPager.show; module: pager
**palette.py** — class: Palette; 15 imports; method: Palette.__getitem__, Palette.__init__, Palette.__rich__, Palette.match; module: palette
**panel.py** — class: Panel; 21 imports; method: Panel.__init__, Panel.__rich_console__, Panel.__rich_measure__, Panel._subtitle, Panel._title, Panel.fit; module: panel
**pretty.py** — class: Node, Pretty, _Line; function: _get_attr_fields, _get_braces_for_array, _get_braces_for_defaultdict, _get_braces_for_deque, _has_default_namedtuple_repr, _ipy_display_hook; 55 imports; method: Node.__str__, Node.check_length, Node.iter_tokens, Node.render, Pretty.__init__, Pretty.__rich_console__; module: pretty
**progress.py** — class: BarColumn, DownloadColumn, FileSizeColumn, MofNCompleteColumn, Progress, ProgressColumn; function: open, track, wrap_file; 63 imports; method: BarColumn.__init__, BarColumn.render, DownloadColumn.__init__, DownloadColumn.render, FileSizeColumn.render, MofNCompleteColumn.__init__; module: progress
**progress_bar.py** — class: ProgressBar; 18 imports; method: ProgressBar.__init__, ProgressBar.__repr__, ProgressBar.__rich_console__, ProgressBar.__rich_measure__, ProgressBar._get_pulse_segments, ProgressBar._render_pulse; module: progress_bar
**prompt.py** — class: Confirm, FloatPrompt, IntPrompt, InvalidResponse, Prompt, PromptBase; 13 imports; method: Confirm.process_response, Confirm.render_default, InvalidResponse.__init__, InvalidResponse.__rich__, PromptBase.__call__, PromptBase.__init__; module: prompt
**protocol.py** — function: is_renderable, rich_cast; 5 imports; module: protocol
**region.py** — class: Region; 1 imports; module: region
**repr.py** — class: ReprError; function: auto, rich_repr; 13 imports; module: repr
**rule.py** — class: Rule; 13 imports; method: Rule.__init__, Rule.__repr__, Rule.__rich_console__, Rule.__rich_measure__, Rule._rule_line; module: rule
**scope.py** — function: render_scope; 14 imports; module: scope
**screen.py** — class: Screen; 11 imports; method: Screen.__init__, Screen.__rich_console__; module: screen
**segment.py** — class: ControlType, Segment, SegmentLines, Segments; 28 imports; method: Segment.__bool__, Segment.__rich_repr__, Segment._split_cells, Segment.adjust_line_length, Segment.align_bottom, Segment.align_middle; module: segment
**spinner.py** — class: Spinner; 17 imports; method: Spinner.__init__, Spinner.__rich_console__, Spinner.__rich_measure__, Spinner.render, Spinner.update; module: spinner
**status.py** — class: Status; 10 imports; method: Status.__enter__, Status.__exit__, Status.__init__, Status.__rich__, Status.console, Status.renderable; module: status
**style.py** — class: Style, StyleStack, _Bit; 24 imports; method: Style.__add__, Style.__bool__, Style.__eq__, Style.__hash__, Style.__init__, Style.__ne__; module: style
**styled.py** — class: Styled; 10 imports; method: Styled.__init__, Styled.__rich_console__, Styled.__rich_measure__; module: styled
**syntax.py** — class: ANSISyntaxTheme, PaddingProperty, PygmentsSyntaxTheme, Syntax, SyntaxTheme, _SyntaxHighlightRange; function: _get_code_index_for_syntax_position; 56 imports; method: ANSISyntaxTheme.__init__, ANSISyntaxTheme.get_background_style, ANSISyntaxTheme.get_style_for_token, PaddingProperty.__get__, PaddingProperty.__set__, PygmentsSyntaxTheme.__init__; module: syntax
**table.py** — class: Column, Row, Table, _Cell; 39 imports; method: Column.cells, Column.copy, Column.flexible, Table.__init__, Table.__rich_console__, Table.__rich_measure__; module: table
**terminal_theme.py** — class: TerminalTheme; 5 imports; method: TerminalTheme.__init__; module: terminal_theme
**text.py** — class: Span, Text; 38 imports; method: Span.__bool__, Span.__repr__, Span.extend, Span.move, Span.right_crop, Span.split; module: text; rationale: [TODO] This is a little inefficient, it is only used by full justify
**theme.py** — class: Theme, ThemeStack, ThemeStackError; 9 imports; method: Theme.__init__, Theme.config, Theme.from_file, Theme.read, ThemeStack.__init__, ThemeStack.pop_theme; module: theme
**themes.py** — 2 imports; module: themes
**traceback.py** — class: Frame, PathHighlighter, Stack, Trace, Traceback, _SyntaxError; function: _iter_syntax_lines, install; 53 imports; method: Traceback.__init__, Traceback.__rich_console__, Traceback._guess_lexer, Traceback._render_stack, Traceback._render_syntax_error, Traceback.extract; module: traceback
**tree.py** — class: Tree; 22 imports; method: Tree.__init__, Tree.__rich_console__, Tree.__rich_measure__, Tree.add; module: tree
**__init__.py** — 1 imports; module: __init__
**__init__.py** — class: Command, sic; function: _find_all_simple, _install_setup_requires, convert_path, findall, setup; 18 imports; method: Command.__init__, Command._ensure_stringlike, Command.ensure_string_list, Command.reinitialize_command; module: __init__; rationale: [NOTE] do not use `setuptools.Distribution` directly, as
**_deprecation_warning.py** — class: SetuptoolsDeprecationWarning; module: _deprecation_warning
**__init__.py** — 2 imports; module: __init__
**_collections.py** — class: DictStack; 2 imports; method: DictStack.__contains__, DictStack.__getitem__, DictStack.__iter__, DictStack.__len__; module: _collections
**_functools.py** — function: pass_none; 1 imports; module: _functools
**_macos_compat.py** — function: bypass_compiler_fixup; 2 imports; module: _macos_compat
**_msvccompiler.py** — class: MSVCCompiler; function: _find_exe, _find_vc2015, _find_vc2017, _find_vcvarsall, _get_vc_env; 16 imports; method: MSVCCompiler.__init__, MSVCCompiler._configure, MSVCCompiler._fallback_spawn, MSVCCompiler._parse_path, MSVCCompiler.compile, MSVCCompiler.create_static_lib; module: _msvccompiler
**archive_util.py** — function: _get_gid, _get_uid, check_archive_formats, make_archive, make_tarball, make_zipfile; 11 imports; module: archive_util
**bcppcompiler.py** — class: BCPPCompiler; 12 imports; method: BCPPCompiler.__init__, BCPPCompiler.compile, BCPPCompiler.create_static_lib, BCPPCompiler.find_library_file, BCPPCompiler.link, BCPPCompiler.object_filenames; module: bcppcompiler
**ccompiler.py** — class: CCompiler; function: gen_lib_options, gen_preprocess_options, get_default_compiler, new_compiler, show_compilers; 18 imports; method: CCompiler.__init__, CCompiler._check_macro_definitions, CCompiler._compile, CCompiler._find_macro, CCompiler._fix_compile_args, CCompiler._fix_lib_args; module: ccompiler
**cmd.py** — class: Command; 14 imports; method: Command.__getattr__, Command.__init__, Command._ensure_stringlike, Command._ensure_tested_string, Command.announce, Command.copy_file; module: cmd
**__init__.py** — module: __init__
**_framework_compat.py** — function: enabled, scheme, vars; 5 imports; module: _framework_compat
**bdist.py** — class: ListCompat, bdist; function: show_formats; 7 imports; method: ListCompat.append, bdist.finalize_options, bdist.initialize_options, bdist.run; module: bdist
**bdist_dumb.py** — class: bdist_dumb; 8 imports; method: bdist_dumb.finalize_options, bdist_dumb.initialize_options, bdist_dumb.run; module: bdist_dumb
**bdist_rpm.py** — class: bdist_rpm; 12 imports; method: bdist_rpm._dist_path, bdist_rpm._format_changelog, bdist_rpm._make_spec_file, bdist_rpm.finalize_options, bdist_rpm.finalize_package_data, bdist_rpm.initialize_options; module: bdist_rpm
**build.py** — class: build; function: show_compilers; 6 imports; method: build.finalize_options, build.has_c_libraries, build.has_ext_modules, build.has_pure_modules, build.has_scripts, build.initialize_options; module: build
**build_clib.py** — class: build_clib; function: show_compilers; 7 imports; method: build_clib.build_libraries, build_clib.check_library_list, build_clib.finalize_options, build_clib.get_library_names, build_clib.get_source_files, build_clib.initialize_options; module: build_clib
**build_ext.py** — class: build_ext; function: show_compilers; 26 imports; method: build_ext._build_extensions_parallel, build_ext._build_extensions_serial, build_ext._filter_build_errors, build_ext.build_extension, build_ext.build_extensions, build_ext.check_extensions_list; module: build_ext
**build_py.py** — class: build_py; 10 imports; method: build_py.build_module, build_py.build_modules, build_py.build_package_data, build_py.build_packages, build_py.byte_compile, build_py.check_module; module: build_py
**build_scripts.py** — class: build_scripts; 9 imports; method: build_scripts._change_mode, build_scripts._change_modes, build_scripts._copy_script, build_scripts._validate_shebang, build_scripts.copy_scripts, build_scripts.finalize_options; module: build_scripts
**check.py** — class: check; 7 imports; method: check._check_rst_data, check.check_metadata, check.check_restructuredtext, check.finalize_options, check.initialize_options, check.run; module: check
**clean.py** — class: clean; 4 imports; method: clean.finalize_options, clean.initialize_options, clean.run; module: clean
**config.py** — class: config; function: dump_file; 10 imports; method: config._check_compiler, config._clean, config._compile, config._gen_temp_sourcefile, config._link, config._preprocess; module: config
**install.py** — class: install; function: _get_implementation, _inject_headers, _load_scheme, _load_schemes, _load_sysconfig_schemes, _pypy_hack; 22 imports; method: install._expand_attrs, install.change_roots, install.convert_paths, install.create_home_path, install.create_path_file, install.dump_dirs; module: install
**install_data.py** — class: install_data; 4 imports; method: install_data.finalize_options, install_data.get_inputs, install_data.get_outputs, install_data.initialize_options, install_data.run; module: install_data
**install_egg_info.py** — class: install_egg_info; function: safe_name, safe_version, to_filename; 6 imports; method: install_egg_info.basename, install_egg_info.finalize_options, install_egg_info.get_outputs, install_egg_info.initialize_options, install_egg_info.run; module: install_egg_info
**install_headers.py** — class: install_headers; 1 imports; method: install_headers.finalize_options, install_headers.get_inputs, install_headers.get_outputs, install_headers.initialize_options, install_headers.run; module: install_headers
**install_lib.py** — class: install_lib; 6 imports; method: install_lib._bytecode_filenames, install_lib._mutate_outputs, install_lib.build, install_lib.byte_compile, install_lib.finalize_options, install_lib.get_inputs; module: install_lib
**install_scripts.py** — class: install_scripts; 4 imports; method: install_scripts.finalize_options, install_scripts.get_inputs, install_scripts.get_outputs, install_scripts.initialize_options, install_scripts.run; module: install_scripts
**py37compat.py** — function: _pythonlib_compat, compose; 2 imports; module: py37compat
**register.py** — class: register; 7 imports; method: register._set_config, register.build_post_data, register.check_metadata, register.classifiers, register.finalize_options, register.initialize_options; module: register
**sdist.py** — class: sdist; function: show_formats; 16 imports; method: sdist._add_defaults_c_libs, sdist._add_defaults_data_files, sdist._add_defaults_ext, sdist._add_defaults_optional, sdist._add_defaults_python, sdist._add_defaults_scripts; module: sdist
**upload.py** — class: upload; 13 imports; method: upload.finalize_options, upload.initialize_options, upload.run, upload.upload_file; module: upload
**config.py** — class: PyPIRCCommand; 4 imports; method: PyPIRCCommand._get_rc_file, PyPIRCCommand._read_pypi_response, PyPIRCCommand._read_pypirc, PyPIRCCommand._store_pypirc, PyPIRCCommand.finalize_options, PyPIRCCommand.initialize_options; module: config
**core.py** — function: gen_usage, run_commands, run_setup, setup; 12 imports; module: core
**cygwinccompiler.py** — class: CygwinCCompiler, Mingw32CCompiler; function: check_config_h, get_msvcr, is_cygwincc; 15 imports; method: CygwinCCompiler.__init__, CygwinCCompiler._compile, CygwinCCompiler._make_out_path, CygwinCCompiler.gcc_version, CygwinCCompiler.link, CygwinCCompiler.out_extensions; module: cygwinccompiler
**debug.py** — 1 imports; module: debug
**dep_util.py** — function: newer, newer_group, newer_pairwise; 3 imports; module: dep_util
**dir_util.py** — function: _build_cmdtuple, copy_tree, create_tree, ensure_relative, mkpath, remove_tree; 6 imports; module: dir_util
**dist.py** — class: Distribution, DistributionMetadata; function: _ensure_list, fix_help_options; 24 imports; method: Distribution.__init__, Distribution._gen_paths, Distribution._get_toplevel_options, Distribution._parse_command_opts, Distribution._set_command_options, Distribution._show_help; module: dist
**errors.py** — class: CCompilerError, CompileError, DistutilsArgError, DistutilsByteCompileError, DistutilsClassError, DistutilsError; module: errors
**extension.py** — class: Extension; function: read_setup_file; 7 imports; method: Extension.__init__, Extension.__repr__; module: extension
**fancy_getopt.py** — class: FancyGetopt, OptionDummy; function: fancy_getopt, translate_longopt, wrap_text; 6 imports; method: FancyGetopt.__init__, FancyGetopt._build_index, FancyGetopt._check_alias_dict, FancyGetopt._grok_option_table, FancyGetopt.add_option, FancyGetopt.generate_help; module: fancy_getopt
**file_util.py** — function: _copy_file_contents, copy_file, move_file, write_file; 14 imports; module: file_util
**filelist.py** — class: FileList, _UniqueDirs; function: _find_all_simple, findall, glob_to_re, translate_pattern; 9 imports; method: FileList.__init__, FileList._parse_template_line, FileList.append, FileList.debug_print, FileList.exclude_pattern, FileList.extend; module: filelist
**log.py** — class: Log; function: set_threshold, set_verbosity; 1 imports; method: Log.__init__, Log._log, Log.debug, Log.error, Log.fatal, Log.info; module: log
**msvc9compiler.py** — class: MSVCCompiler, MacroExpander, Reg; function: find_vcvarsall, get_build_version, normalize_and_reduce_paths, query_vcvarsall, removeDuplicates; 15 imports; method: MSVCCompiler.__init__, MSVCCompiler._remove_visual_c_ref, MSVCCompiler.compile, MSVCCompiler.create_static_lib, MSVCCompiler.find_exe, MSVCCompiler.find_library_file; module: msvc9compiler
**msvccompiler.py** — class: MSVCCompiler, MacroExpander; function: convert_mbcs, get_build_architecture, get_build_version, normalize_and_reduce_paths, read_keys, read_values; 16 imports; method: MSVCCompiler.__init__, MSVCCompiler.compile, MSVCCompiler.create_static_lib, MSVCCompiler.find_exe, MSVCCompiler.find_library_file, MSVCCompiler.get_msvc_paths; module: msvccompiler
**py38compat.py** — function: aix_platform; 1 imports; module: py38compat
**py39compat.py** — function: add_ext_suffix_39; 3 imports; module: py39compat
**spawn.py** — function: find_executable, spawn; 8 imports; module: spawn
**sysconfig.py** — function: _get_python_inc_from_config, _get_python_inc_nt, _get_python_inc_posix, _get_python_inc_posix_prefix, _get_python_inc_posix_python, _is_parent; 11 imports; module: sysconfig
**text_file.py** — class: TextFile; 1 imports; method: TextFile.__init__, TextFile.close, TextFile.error, TextFile.gen_error, TextFile.open, TextFile.readline; module: text_file
**unixccompiler.py** — class: UnixCCompiler; function: _linker_params, _split_aix, _split_env; 18 imports; method: UnixCCompiler._compile, UnixCCompiler._is_gcc, UnixCCompiler._library_root, UnixCCompiler.create_static_lib, UnixCCompiler.find_library_file, UnixCCompiler.library_dir_option; module: unixccompiler
**util.py** — function: _clear_cached_macosx_ver, _init_regex, _subst_compat, byte_compile, change_root, check_environ; 20 imports; module: util
**version.py** — class: LooseVersion, StrictVersion, Version; function: suppress_known_deprecation; 3 imports; method: LooseVersion.__repr__, LooseVersion.__str__, LooseVersion._cmp, LooseVersion.parse, StrictVersion.__str__, StrictVersion._cmp; module: version
**versionpredicate.py** — class: VersionPredicate; function: splitUp, split_provision; 3 imports; method: VersionPredicate.__init__, VersionPredicate.__str__, VersionPredicate.satisfied_by; module: versionpredicate
**_entry_points.py** — function: _, by_group_and_name, ensure_valid, load, load_group, render; 8 imports; module: _entry_points
**_imp.py** — function: find_module, find_spec, get_frozen_object, get_module; 4 imports; module: _imp
**_importlib.py** — function: disable_importlib_metadata_finder; 7 imports; module: _importlib
**_itertools.py** — function: ensure_unique; 1 imports; module: _itertools
**_path.py** — function: ensure_directory, same_path; 2 imports; module: _path
**_reqs.py** — function: parse, parse_strings; 2 imports; module: _reqs
**__init__.py** — class: Deprecated, DeprecatedList, DeprecatedTuple, Distribution, DistributionFinder, EntryPoint; function: _top_level_declared, _top_level_inferred, distribution, distributions, entry_points, files; 36 imports; method: Deprecated.__contains__, Deprecated.__getitem__, Deprecated.__iter__, Deprecated.get, Deprecated.keys, Deprecated.values; module: __init__
**_adapters.py** — class: Message; 4 imports; method: Message.__init__, Message.__iter__, Message.__new__, Message._repair_headers, Message.json; module: _adapters
**_collections.py** — class: FreezableDefaultDict, Pair; 1 imports; method: FreezableDefaultDict.__missing__, FreezableDefaultDict.freeze, Pair.parse; module: _collections
**_compat.py** — class: NullFinder; function: disable_stdlib_finder, install, pypy_partial; 4 imports; method: NullFinder.find_spec; module: _compat
**_functools.py** — function: method_cache, pass_none; 2 imports; module: _functools
**_itertools.py** — function: always_iterable, unique_everseen; 1 imports; module: _itertools
**_meta.py** — class: PackageMetadata, SimplePath; 7 imports; method: PackageMetadata.__contains__, PackageMetadata.__getitem__, PackageMetadata.__iter__, PackageMetadata.__len__, PackageMetadata.get_all, PackageMetadata.json; module: _meta
**_text.py** — class: FoldedCase; 2 imports; method: FoldedCase.__contains__, FoldedCase.__eq__, FoldedCase.__gt__, FoldedCase.__hash__, FoldedCase.__lt__, FoldedCase.__ne__; module: _text
**__init__.py** — 12 imports; module: __init__
**_adapters.py** — class: CompatibilityFiles, SpecLoaderAdapter, TraversableResourcesLoader; function: _io_wrapper, wrap_spec; 3 imports; method: CompatibilityFiles.__getattr__, CompatibilityFiles.__init__, CompatibilityFiles._native, CompatibilityFiles._reader, CompatibilityFiles.files, SpecLoaderAdapter.__getattr__; module: _adapters
**_common.py** — function: _, _tempfile, as_file, files, from_package, get_package; 12 imports; module: _common
**_compat.py** — class: TraversableResourcesLoader; function: wrap_spec; 10 imports; method: TraversableResourcesLoader.__init__, TraversableResourcesLoader.get_resource_reader, TraversableResourcesLoader.path; module: _compat
**_itertools.py** — function: unique_everseen; 8 imports; module: _itertools
**_legacy.py** — function: contents, deprecated, is_resource, normalize_path, open_binary, open_text; 12 imports; module: _legacy
**abc.py** — class: ResourceReader, Traversable, TraversableResources; 6 imports; method: ResourceReader.contents, ResourceReader.is_resource, ResourceReader.open_resource, ResourceReader.resource_path, Traversable.__truediv__, Traversable.is_dir; module: abc
**readers.py** — class: FileReader, MultiplexedPath, NamespaceReader, ZipReader; function: remove_duplicates; 6 imports; method: FileReader.__init__, FileReader.files, FileReader.resource_path, MultiplexedPath.__init__, MultiplexedPath.__repr__, MultiplexedPath.is_dir; module: readers
**simple.py** — class: ResourceContainer, ResourceHandle, SimpleReader, TraversableReader; 7 imports; method: ResourceContainer.__init__, ResourceContainer.is_dir, ResourceContainer.is_file, ResourceContainer.iterdir, ResourceContainer.joinpath, ResourceContainer.open; module: simple
**context.py** — class: ExceptionTrap, suppress; function: infer_compression, null, pushd, repo_context, tarball_context, temp_dir; 7 imports; method: ExceptionTrap.__bool__, ExceptionTrap.__enter__, ExceptionTrap.__exit__, ExceptionTrap.__init__, ExceptionTrap.passes, ExceptionTrap.raises; module: context
**functools.py** — class: Throttler; function: _special_method_cache, apply, assign_params, call_aside, compose, except_; 9 imports; method: Throttler.__call__, Throttler.__get__, Throttler.__init__, Throttler._wait, Throttler.reset; module: functools
**__init__.py** — class: FoldedCase, SeparatedValues, Splitter, Stripper, WordSet; function: _, _nonblank, drop_comment, indent, is_binary, is_decodable; 9 imports; method: FoldedCase.__contains__, FoldedCase.__eq__, FoldedCase.__gt__, FoldedCase.__hash__, FoldedCase.__lt__, FoldedCase.__ne__; module: __init__
**__init__.py** — 2 imports; module: __init__
**more.py** — class: AbortThread, SequenceView, UnequalIterablesError, bucket, callback_iter, countable; function: _islice_helper, _sample_unweighted, _sample_weighted, _zip_equal_generator, adjacent, all_unique; 48 imports; method: SequenceView.__getitem__, SequenceView.__init__, SequenceView.__len__, SequenceView.__repr__, UnequalIterablesError.__init__, bucket.__contains__; module: more
**recipes.py** — function: _pairwise, all_equal, consume, convolve, dotproduct, first_true; 17 imports; module: recipes
**ordered_set.py** — class: OrderedSet; function: is_iterable; 6 imports; method: OrderedSet.__and__, OrderedSet.__contains__, OrderedSet.__eq__, OrderedSet.__getitem__, OrderedSet.__getstate__, OrderedSet.__init__; module: ordered_set
**__about__.py** — module: __about__
**__init__.py** — 8 imports; module: __init__
**_manylinux.py** — class: _ELFFileHeader, _GLibCVersion; function: _get_elf_header, _get_glibc_version, _glibc_version_string, _glibc_version_string_confstr, _glibc_version_string_ctypes, _have_compatible_abi; 15 imports; method: _ELFFileHeader.__init__; module: _manylinux
**_musllinux.py** — class: _MuslVersion; function: _get_musl_version, _parse_ld_musl_from_elf, _parse_musl_version, _read_unpacked, platform_tags; 14 imports; module: _musllinux
**_structures.py** — class: InfinityType, NegativeInfinityType; method: InfinityType.__eq__, InfinityType.__ge__, InfinityType.__gt__, InfinityType.__hash__, InfinityType.__le__, InfinityType.__lt__; module: _structures
**markers.py** — class: InvalidMarker, Marker, Node, Op, Undefined, UndefinedComparison; function: _coerce_parse_result, _eval_op, _evaluate_markers, _format_marker, _get_env, default_environment; 22 imports; method: Marker.__init__, Marker.__repr__, Marker.__str__, Marker.evaluate, Node.__init__, Node.__repr__; module: markers
**requirements.py** — class: InvalidRequirement, Requirement; 21 imports; method: Requirement.__init__, Requirement.__repr__, Requirement.__str__; module: requirements; rationale: [TODO] Can we normalize the name and extra name?, [TODO] Can we test whether something is contained within a requirement?
**specifiers.py** — class: BaseSpecifier, InvalidSpecifier, LegacySpecifier, Specifier, SpecifierSet, _IndividualSpecifier; function: _is_not_suffix, _pad_version, _require_version_compare, _version_split; 20 imports; method: BaseSpecifier.__eq__, BaseSpecifier.__hash__, BaseSpecifier.__str__, BaseSpecifier.contains, BaseSpecifier.filter, BaseSpecifier.prereleases; module: specifiers; rationale: [NOTE] This means that 1.0.dev1 would not be contained in something, [NOTE] This use of all() here means that an empty set of specifiers
**tags.py** — class: Tag; function: _abi3_applies, _cpython_abis, _generic_abi, _generic_platforms, _get_config_var, _linux_platforms; 17 imports; method: Tag.__eq__, Tag.__hash__, Tag.__init__, Tag.__repr__, Tag.__str__, Tag.abi; module: tags; rationale: [TODO] Need to care about 32-bit PPC for ppc64 through 10.2?
**utils.py** — class: InvalidSdistFilename, InvalidWheelFilename; function: canonicalize_name, canonicalize_version, parse_sdist_filename, parse_wheel_filename; 10 imports; module: utils
**version.py** — class: InvalidVersion, LegacyVersion, Version, _BaseVersion; function: _cmpkey, _legacy_cmpkey, _parse_letter_version, _parse_local_version, _parse_version_parts, parse; 15 imports; method: LegacyVersion.__init__, LegacyVersion.__repr__, LegacyVersion.__str__, LegacyVersion.base_version, LegacyVersion.dev, LegacyVersion.epoch; module: version
**__init__.py** — class: version_info; 17 imports; method: version_info.__repr__, version_info.__str__, version_info.__version__; module: __init__
**actions.py** — class: OnlyOnce; function: match_only_at_col, remove_quotes, replace_with, with_attribute, with_class; 3 imports; method: OnlyOnce.__call__, OnlyOnce.__init__, OnlyOnce.reset; module: actions
**common.py** — class: pyparsing_common; 5 imports; method: pyparsing_common.convert_to_date, pyparsing_common.convert_to_datetime, pyparsing_common.strip_html_tags; module: common
**core.py** — class: And, AtLineStart, AtStringStart, CaselessKeyword, CaselessLiteral, Char; function: _default_exception_debug_action, _default_start_debug_action, _default_success_debug_action, _should_enable_warnings, _trim_arity, autoname_elements; 46 imports; method: And.__iadd__, And.__init__, And._checkRecursion, And._generateDefaultName, And.parseImpl, And.streamline; module: core
**__init__.py** — class: AnnotatedItem, ConverterState, EachItem, EditablePartial, ElementState; function: _apply_diagram_item_enhancements, _should_vertical, _to_diagram_element, _visible_exprs, _worth_extracting, railroad_to_html; 14 imports; method: AnnotatedItem.__init__, ConverterState.__contains__, ConverterState.__delitem__, ConverterState.__getitem__, ConverterState.__init__, ConverterState.__setitem__; module: __init__; rationale: [NOTE] ideally this would be a dataclass, but we're supporting Python 3.5+ so we can't , [NOTE] this should be a dataclass, but we have to support Python 3.5
**exceptions.py** — class: ExceptionWordUnicode, ParseBaseException, ParseException, ParseFatalException, ParseSyntaxException, RecursiveGrammarException; 10 imports; method: ParseBaseException.__init__, ParseBaseException.__repr__, ParseBaseException.__str__, ParseBaseException._from_exception, ParseBaseException.col, ParseBaseException.column; module: exceptions
**helpers.py** — class: OpAssoc; function: _makeTags, counted_array, delimited_list, dict_of, indentedBlock, infix_notation; 8 imports; module: helpers
**results.py** — class: ParseResults, _ParseResultsWithOffset; 8 imports; method: ParseResults.__add__, ParseResults.__bool__, ParseResults.__contains__, ParseResults.__delitem__, ParseResults.__dir__, ParseResults.__getattr__; module: results
**testing.py** — class: pyparsing_test; 7 imports; method: pyparsing_test.with_line_numbers; module: testing
**unicode.py** — class: _lazyclassproperty, pyparsing_unicode, unicode_set; 5 imports; method: _lazyclassproperty.__get__, _lazyclassproperty.__init__, unicode_set._chars_for_ranges, unicode_set.alphanums, unicode_set.alphas, unicode_set.identbodychars; module: unicode
**util.py** — class: LRUMemo, UnboundedMemo, _FifoCache, _UnboundedCache, __config_flags; function: _collapse_string_to_ranges, _escape_regex_range_chars, _flatten, col, line, lineno; 8 imports; method: LRUMemo.__delitem__, LRUMemo.__getitem__, LRUMemo.__init__, LRUMemo.__setitem__, LRUMemo.clear, UnboundedMemo.__delitem__; module: util
**__init__.py** — 3 imports; module: __init__
**_parser.py** — class: Flags, NestedDict, Output, TOMLDecodeError; function: create_dict_rule, create_list_rule, is_unicode_scalar_value, key_value_rule, load, loads; 16 imports; method: Flags.__init__, Flags.add_pending, Flags.finalize_pending, Flags.is_, Flags.set, Flags.unset_all; module: _parser; rationale: [IMPORTANT] order conditions based on speed of checking and likelihood
**_re.py** — function: cached_tz, match_to_datetime, match_to_localtime, match_to_number; 11 imports; module: _re
**_types.py** — 3 imports; module: _types
**typing_extensions.py** — class: _ExtensionsGenericMeta; function: IntVar, _check_generic, _concatenate_getitem, _get_protocol_attrs, _gorg, _is_callable_members_only; 15 imports; method: _ExtensionsGenericMeta.__subclasscheck__; module: typing_extensions; rationale: [NOTE] Modeled after _Final's implementation when _FinalTypingBase available
**zipp.py** — class: CompleteDirs, FastLookup, Path; function: _ancestry, _difference, _parents, _pathlib_compat; 8 imports; method: CompleteDirs._implied_dirs, CompleteDirs._name_set, CompleteDirs.make, CompleteDirs.namelist, CompleteDirs.resolve_dir, FastLookup._name_set; module: zipp
**archive_util.py** — class: UnrecognizedFormat; function: _iter_open_tar, _resolve_tar_file_or_dir, _unpack_zipfile_obj, default_filter, unpack_archive, unpack_directory; 8 imports; module: archive_util
**build_meta.py** — class: Distribution, SetupRequirementsError, _BuildMetaBackend, _BuildMetaLegacyBackend, _ConfigSettingsTranslator; function: _file_with_extension, _get_immediate_subdirectories, _open_setup_script, no_install_setup_requires, suppress_known_deprecation; 22 imports; method: Distribution.fetch_build_eggs, Distribution.patch, SetupRequirementsError.__init__, _BuildMetaBackend._bubble_up_info_directory, _BuildMetaBackend._build_with_temp_dir, _BuildMetaBackend._find_info_directory; module: build_meta
**__init__.py** — 2 imports; module: __init__
**alias.py** — class: alias; function: format_alias, shquote; 4 imports; method: alias.finalize_options, alias.initialize_options, alias.run; module: alias
**bdist_egg.py** — class: bdist_egg; function: _get_purelib, analyze_egg, can_scan, iter_symbols, make_zipfile, scan_module; 17 imports; method: bdist_egg.call_command, bdist_egg.copy_metadata_to, bdist_egg.do_install_data, bdist_egg.finalize_options, bdist_egg.gen_header, bdist_egg.get_ext_outputs; module: bdist_egg
**bdist_rpm.py** — class: bdist_rpm; 3 imports; method: bdist_rpm._make_spec_file, bdist_rpm.run; module: bdist_rpm
**build.py** — class: SubCommand, build; 10 imports; method: SubCommand.finalize_options, SubCommand.get_output_mapping, SubCommand.get_outputs, SubCommand.get_source_files, SubCommand.initialize_options, SubCommand.run; module: build
**build_clib.py** — class: build_clib; 4 imports; method: build_clib.build_libraries; module: build_clib
**build_ext.py** — class: build_ext; function: _customize_compiler_for_shlib, get_abi3_suffix, if_dl; 21 imports; method: build_ext.__get_output_extensions, build_ext.__get_stubs_outputs, build_ext._compile_and_remove_stub, build_ext._get_equivalent_stub, build_ext._get_inplace_equivalent, build_ext._get_output_mapping; module: build_ext
**build_py.py** — class: _IncludePackageDataAbuse, build_py; function: assert_relative, make_writable; 22 imports; method: _IncludePackageDataAbuse.__init__, _IncludePackageDataAbuse.importable_subpackage, _IncludePackageDataAbuse.is_module, _IncludePackageDataAbuse.warn, build_py.__getattr__, build_py._filter_build_files; module: build_py
**develop.py** — class: VersionlessRequirement, develop; 11 imports; method: VersionlessRequirement.__getattr__, VersionlessRequirement.__init__, VersionlessRequirement.as_requirement, develop._resolve_setup_path, develop.finalize_options, develop.initialize_options; module: develop
**dist_info.py** — class: dist_info; function: _copy, _rm, _safe, _version; 12 imports; method: dist_info._maybe_bkp_dir, dist_info.finalize_options, dist_info.initialize_options, dist_info.run; module: dist_info; rationale: [TODO] if bdist_wheel if merged into setuptools, just add "keep_egg_info" there
**easy_install.py** — class: CommandSpec, EasyInstallDeprecationWarning, PthDistributions, RewritePthDistributions, ScriptWriter, WindowsCommandSpec; function: _collect_zipimporter_cache_entries, _first_line_re, _one_liner, _pythonpath, _remove_and_clear_zip_directory_cache_data, _to_bytes; 64 imports; method: CommandSpec._extract_options, CommandSpec._render, CommandSpec._strip_quotes, CommandSpec._sys_executable, CommandSpec.as_header, CommandSpec.best; module: easy_install; rationale: [FIXME] 'easy_install.exe_to_egg' is too complex (12), [FIXME] 'easy_install.install_egg' is too complex (11), [FIXME] 'easy_install.process_distribution' is too complex (12), [TODO] This code doesn't make sense. What is it trying to do?, [TODO] self.report_extras(req, dist)
**editable_wheel.py** — class: EditableStrategy, InformationOnly, LinksNotSupported, _EditableMode, _LinkTree, _NamespaceInstaller; function: _absolute_root, _can_symlink_files, _empty_dir, _find_namespaces, _find_package_roots, _find_packages; 34 imports; method: EditableStrategy.__call__, EditableStrategy.__enter__, EditableStrategy.__exit__, _EditableMode.convert, _LinkTree.__call__, _LinkTree.__enter__; module: editable_wheel; rationale: [TODO] Once plugins/customisations had the chance to catch up, replace, [TODO] Remove `compat` after Dec/2022., [XXX] Only required to support the deprecated namespace practice
**egg_info.py** — class: EggInfoDeprecationWarning, FileList, InfoCommon, egg_info, manifest_maker; function: _write_requirements, get_pkg_info_revision, overwrite_arg, translate_pattern, warn_depends_obsolete, write_arg; 31 imports; method: FileList.__init__, FileList._remove_files, FileList._repair, FileList._safe_path, FileList.append, FileList.exclude; module: egg_info; rationale: [NOTE] we need to capture the current value returned
**install.py** — class: install; 7 imports; method: install._called_from_setup, install.do_egg_install, install.finalize_options, install.handle_extra_path, install.initialize_options, install.run; module: install
**install_egg_info.py** — class: install_egg_info; 8 imports; method: install_egg_info.copytree, install_egg_info.finalize_options, install_egg_info.get_outputs, install_egg_info.initialize_options, install_egg_info.run; module: install_egg_info
**install_lib.py** — class: install_lib; 7 imports; method: install_lib._all_packages, install_lib._exclude_pkg_path, install_lib._gen_exclusion_paths, install_lib._get_SVEM_NSPs, install_lib.copy_tree, install_lib.get_exclusions; module: install_lib; rationale: [TODO] is it necessary to short-circuit here? i.e. what's the cost
**install_scripts.py** — class: install_scripts; 11 imports; method: install_scripts.initialize_options, install_scripts.run, install_scripts.write_script; module: install_scripts
**py36compat.py** — class: sdist_add_defaults; 4 imports; method: sdist_add_defaults._add_defaults_c_libs, sdist_add_defaults._add_defaults_data_files, sdist_add_defaults._add_defaults_ext, sdist_add_defaults._add_defaults_optional, sdist_add_defaults._add_defaults_python, sdist_add_defaults._add_defaults_scripts; module: py36compat
**register.py** — class: register; 3 imports; method: register.run; module: register
**rotate.py** — class: rotate; 7 imports; method: rotate.finalize_options, rotate.initialize_options, rotate.run; module: rotate
**saveopts.py** — class: saveopts; 2 imports; method: saveopts.run; module: saveopts
**sdist.py** — class: sdist; function: walk_revctrl; 10 imports; method: sdist._add_data_files, sdist._add_defaults_build_sub_commands, sdist._add_defaults_data_files, sdist._add_defaults_optional, sdist._add_defaults_python, sdist._default_to_gztar; module: sdist
**setopt.py** — class: option_base, setopt; function: config_file, edit_config; 7 imports; method: option_base.finalize_options, option_base.initialize_options, setopt.finalize_options, setopt.initialize_options, setopt.run; module: setopt
**test.py** — class: NonDataProperty, ScanningLoader, test; 21 imports; method: NonDataProperty.__get__, NonDataProperty.__init__, ScanningLoader.__init__, ScanningLoader.loadTestsFromModule, test._argv, test._resolve_as_ep; module: test
**upload.py** — class: upload; 3 imports; method: upload.run; module: upload
**upload_docs.py** — class: upload_docs; function: _encode; 16 imports; method: upload_docs._build_multipart, upload_docs._build_part, upload_docs.create_zipfile, upload_docs.finalize_options, upload_docs.has_sphinx, upload_docs.initialize_options; module: upload_docs
**__init__.py** — function: _deprecation_notice; 8 imports; module: __init__
**_apply_pyprojecttoml.py** — class: _WouldIgnoreField; function: _apply_project_table, _apply_tool_table, _attrgetter, _copy_command_options, _dependencies, _guess_content_type; 26 imports; method: _WouldIgnoreField.message; module: _apply_pyprojecttoml; rationale: [TODO] Set fields back to `None` once the feature stabilizes
**__init__.py** — function: validate; 11 imports; module: __init__
**error_reporting.py** — class: ValidationError, _ErrorFormatting, _SummaryWriter; function: _separate_terms, detailed_errors; 17 imports; method: ValidationError._from_jsonschema, _ErrorFormatting.__init__, _ErrorFormatting.__str__, _ErrorFormatting._expand_details, _ErrorFormatting._expand_summary, _ErrorFormatting._simplify_name; module: error_reporting
**extra_validations.py** — class: RedefiningStaticFieldAsDynamic; function: validate_project_dynamic; 3 imports; module: extra_validations
**fastjsonschema_exceptions.py** — class: JsonSchemaDefinitionException, JsonSchemaException, JsonSchemaValueException; 1 imports; method: JsonSchemaValueException.__init__, JsonSchemaValueException.path, JsonSchemaValueException.rule_definition; module: fastjsonschema_exceptions
**fastjsonschema_validations.py** — function: validate, validate_https___docs_python_org_3_install, validate_https___packaging_python_org_en_latest_specifications_declaring_build_dependencies, validate_https___packaging_python_org_en_latest_specifications_declaring_project_metadata, validate_https___packaging_python_org_en_latest_specifications_declaring_project_metadata___definitions_author, validate_https___packaging_python_org_en_latest_specifications_declaring_project_metadata___definitions_dependency; 2 imports; module: fastjsonschema_validations
**formats.py** — class: _TroveClassifier; function: _download_classifiers, pep440, pep508_identifier, pep508_versionspec, pep517_backend_reference, python_entrypoint_group; 13 imports; method: _TroveClassifier.__call__, _TroveClassifier.__init__, _TroveClassifier._disable_download; module: formats
**expand.py** — class: EnsurePackagesDiscovered, LazyMappingProxy, StaticModule; function: _assert_local, _filter_existing_files, _find_module, _find_spec, _load_spec, _nest_path; 35 imports; method: EnsurePackagesDiscovered.__call__, EnsurePackagesDiscovered.__enter__, EnsurePackagesDiscovered.__exit__, EnsurePackagesDiscovered.__init__, EnsurePackagesDiscovered._get_package_dir, EnsurePackagesDiscovered.package_dir; module: expand
**pyprojecttoml.py** — class: _BetaConfiguration, _ConfigExpander, _EnsurePackagesDiscovered, _InvalidFile; function: _ignore_errors, _parse_requirements_list, _skip_bad_config, apply_configuration, expand_configuration, load_file; 21 imports; method: _ConfigExpander.__init__, _ConfigExpander._canonic_package_data, _ConfigExpander._ensure_dist, _ConfigExpander._ensure_previously_set, _ConfigExpander._expand_all_dynamic, _ConfigExpander._expand_cmdclass; module: pyprojecttoml; rationale: [TODO] After the previous statement is removed the try/except can be replaced, [TODO] Don't set field when support for pyproject.toml stabilizes, [TODO] Remove the following once the feature stabilizes:, [TODO] Remove the following once the feature stabilizes:
**setupcfg.py** — class: ConfigHandler, ConfigMetadataHandler, ConfigOptionsHandler; function: _apply, _get_option, _warn_accidental_env_marker_misconfig, apply_configuration, configuration_to_dict, parse_configuration; 30 imports; method: ConfigHandler.__init__, ConfigHandler.__setitem__, ConfigHandler._deprecated_config_handler, ConfigHandler._exclude_files_parser, ConfigHandler._get_parser_compound, ConfigHandler._parse_attr; module: setupcfg
**dep_util.py** — function: newer_pairwise_group; 1 imports; module: dep_util
**depends.py** — class: Require; function: _update_globals, extract_constant, get_module_constant, maybe_close; 10 imports; method: Require.__init__, Require.full_name, Require.get_version, Require.is_current, Require.is_present, Require.version_ok; module: depends
**discovery.py** — class: ConfigDiscovery, FlatLayoutModuleFinder, FlatLayoutPackageFinder, ModuleFinder, PEP420PackageFinder, PackageFinder; function: _find_packages_within, _valid_name, construct_package_dir, find_package_path, find_parent_package, remove_nested_packages; 21 imports; method: ConfigDiscovery.__call__, ConfigDiscovery.__init__, ConfigDiscovery._analyse_explicit_layout, ConfigDiscovery._analyse_flat_layout, ConfigDiscovery._analyse_flat_modules, ConfigDiscovery._analyse_flat_packages; module: discovery
**dist.py** — class: DistDeprecationWarning, Distribution; function: _check_extra, _get_unpatched, _read_field_from_msg, _read_field_unescaped_from_msg, _read_list_from_msg, _read_payload_from_msg; 47 imports; method: Distribution.__init__, Distribution._clean_req, Distribution._convert_extras_requirements, Distribution._exclude_misc, Distribution._exclude_packages, Distribution._expand_patterns; module: dist; rationale: [FIXME] 'Distribution._parse_config_files' is too complex (14), [FIXME] 'Distribution._set_command_options' is too complex (14), [TODO] Replace with `raise ValueError("newlines not allowed")`
**errors.py** — class: PackageDiscoveryError, RemovedCommandError; 1 imports; module: errors
**extension.py** — class: Extension, Library; function: _have_cython; 6 imports; method: Extension.__init__, Extension._convert_pyx_sources_to_lang; module: extension
**__init__.py** — class: VendorImporter; 2 imports; method: VendorImporter.__init__, VendorImporter._module_matches_namespace, VendorImporter.create_module, VendorImporter.exec_module, VendorImporter.find_spec, VendorImporter.install; module: __init__
**glob.py** — function: _iglob, _isrecursive, _rlistdir, escape, glob, glob0; 3 imports; module: glob
**installer.py** — function: _fixup_find_links, fetch_build_egg, strip_marker; 11 imports; module: installer
**launch.py** — function: run; 2 imports; module: launch
**logging.py** — function: _not_warning, configure, set_threshold; 4 imports; module: logging
**monkey.py** — function: _get_mro, _patch_distribution_metadata, get_unpatched, get_unpatched_class, get_unpatched_function, patch_all; 8 imports; module: monkey
**msvc.py** — class: EnvironmentInfo, PlatformInfo, RegistryInfo, SystemInfo; function: _augment_exception, _msvc14_find_vc2015, _msvc14_find_vc2017, _msvc14_find_vcvarsall, _msvc14_get_vc_env, msvc14_gen_lib_options; 21 imports; method: EnvironmentInfo.FSharp, EnvironmentInfo.FxTools, EnvironmentInfo.HTMLHelpWorkshop, EnvironmentInfo.MSBuild, EnvironmentInfo.NetFxSDKIncludes, EnvironmentInfo.NetFxSDKLibraries; module: msvc; rationale: [NOTE] No download link available from Microsoft.
**namespaces.py** — class: DevelopInstaller, Installer; 3 imports; method: DevelopInstaller._get_root, DevelopInstaller._get_target, Installer._gen_nspkg_line, Installer._get_all_ns_packages, Installer._get_root, Installer._get_target; module: namespaces
**package_index.py** — class: ContentChecker, Credential, HashChecker, PackageIndex, PyPIConfig; function: _encode_auth, _splituser, decode_entity, distros_for_filename, distros_for_location, distros_for_url; 37 imports; method: ContentChecker.feed, ContentChecker.is_valid, ContentChecker.report, Credential.__init__, Credential.__iter__, Credential.__str__; module: package_index; rationale: [FIXME] 'PackageIndex.process_url' is too complex (14)
**py34compat.py** — 2 imports; module: py34compat
**sandbox.py** — class: AbstractSandbox, DirectorySandbox, ExceptionSaver, SandboxViolation, UnpickleableException; function: _clear_modules, _execfile, _needs_hiding, hide_setuptools, override_temp, pushd; 17 imports; method: AbstractSandbox.__enter__, AbstractSandbox.__exit__, AbstractSandbox.__init__, AbstractSandbox._copy, AbstractSandbox._mk_dual_path_wrapper, AbstractSandbox._mk_query; module: sandbox
**unicode_utils.py** — function: decompose, filesys_decode, try_encode; 2 imports; module: unicode_utils
**version.py** — 1 imports; module: version
**wheel.py** — class: Wheel; function: disable_info_traces, unpack; 16 imports; method: Wheel.__init__, Wheel._convert_metadata, Wheel._fix_namespace_packages, Wheel._install_as_egg, Wheel._move_data_entries, Wheel.egg_name; module: wheel; rationale: [NOTE] Evaluate and strip markers now,
**windows_support.py** — function: hide_file, windows_only; 2 imports; module: windows_support
**__init__.py** — 3 imports; module: __init__
**_utils.py** — function: collapse_excgroups; 4 imports; module: _utils
**event.py** — class: JSONServerSentEvent, ServerSentEvent; function: ensure_bytes; 6 imports; method: JSONServerSentEvent.__init__, ServerSentEvent.__init__, ServerSentEvent.encode; module: event
**sse.py** — class: AppStatus, EventSourceResponse, SendTimeoutError, _ShutdownState; function: _ensure_watcher_started_on_this_loop, _get_shutdown_state, _get_uvicorn_server, _shutdown_watcher, _wrap_websocket_denial_send; 31 imports; method: AppStatus.disable_automatic_graceful_drain, AppStatus.enable_automatic_graceful_drain_mode, AppStatus.handle_exit, EventSourceResponse.__call__, EventSourceResponse.__init__, EventSourceResponse._listen_for_disconnect; module: sse
**__init__.py** — module: __init__
**_exception_handler.py** — function: _lookup_exception_handler, wrap_app_handling_exceptions; 13 imports; module: _exception_handler
**_utils.py** — class: AwaitableOrContextManager, AwaitableOrContextManagerWrapper, SupportsAsyncClose; function: create_collapsing_task_group, get_route_path, is_async_callable; 21 imports; method: AwaitableOrContextManagerWrapper.__aenter__, AwaitableOrContextManagerWrapper.__aexit__, AwaitableOrContextManagerWrapper.__await__, AwaitableOrContextManagerWrapper.__init__, SupportsAsyncClose.close; module: _utils
**applications.py** — class: Starlette; 24 imports; method: Starlette.__call__, Starlette.__init__, Starlette.add_exception_handler, Starlette.add_middleware, Starlette.add_route, Starlette.build_middleware_stack; module: applications
**authentication.py** — class: AuthCredentials, AuthenticationBackend, AuthenticationError, BaseUser, SimpleUser, UnauthenticatedUser; function: has_required_scope, requires; 14 imports; method: AuthCredentials.__init__, AuthenticationBackend.authenticate, BaseUser.display_name, BaseUser.identity, BaseUser.is_authenticated, SimpleUser.__init__; module: authentication
**background.py** — class: BackgroundTask, BackgroundTasks; 7 imports; method: BackgroundTask.__call__, BackgroundTask.__init__, BackgroundTasks.__call__, BackgroundTasks.__init__, BackgroundTasks.add_task; module: background
**concurrency.py** — class: _StopIteration; function: _next, iterate_in_threadpool, run_in_threadpool, run_until_first_complete; 12 imports; module: concurrency
**config.py** — class: Config, Environ, EnvironError, undefined; 11 imports; method: Config.__call__, Config.__init__, Config._perform_cast, Config._read_file, Config.get, Environ.__delitem__; module: config
**convertors.py** — class: Convertor, FloatConvertor, IntegerConvertor, PathConvertor, StringConvertor, UUIDConvertor; function: register_url_convertor; 7 imports; method: Convertor.convert, Convertor.to_string, FloatConvertor.convert, FloatConvertor.to_string, IntegerConvertor.convert, IntegerConvertor.to_string; module: convertors
**datastructures.py** — class: Address, CommaSeparatedStrings, FormData, Headers, ImmutableMultiDict, MultiDict; 23 imports; method: CommaSeparatedStrings.__getitem__, CommaSeparatedStrings.__init__, CommaSeparatedStrings.__iter__, CommaSeparatedStrings.__len__, CommaSeparatedStrings.__repr__, CommaSeparatedStrings.__str__; module: datastructures
**endpoints.py** — class: HTTPEndpoint, WebSocketEndpoint; 18 imports; method: HTTPEndpoint.__await__, HTTPEndpoint.__init__, HTTPEndpoint.dispatch, HTTPEndpoint.method_not_allowed, WebSocketEndpoint.__await__, WebSocketEndpoint.__init__; module: endpoints
**exceptions.py** — class: HTTPException, StarletteDeprecationWarning, WebSocketException; 3 imports; method: HTTPException.__init__, HTTPException.__repr__, HTTPException.__str__, WebSocketException.__init__, WebSocketException.__repr__, WebSocketException.__str__; module: exceptions
**formparsers.py** — class: FormMessage, FormParser, MultiPartException, MultiPartParser, MultipartPart; function: _user_safe_decode; 17 imports; method: FormParser.__init__, FormParser.on_end, FormParser.on_field_data, FormParser.on_field_end, FormParser.on_field_name, FormParser.on_field_start; module: formparsers
**__init__.py** — class: Middleware, _MiddlewareFactory; 7 imports; method: Middleware.__init__, Middleware.__iter__, Middleware.__repr__, _MiddlewareFactory.__call__; module: __init__
**authentication.py** — class: AuthenticationMiddleware; 13 imports; method: AuthenticationMiddleware.__call__, AuthenticationMiddleware.__init__, AuthenticationMiddleware.default_on_error; module: authentication
**base.py** — class: BaseHTTPMiddleware, _CachedRequest, _StreamingResponse; 19 imports; method: BaseHTTPMiddleware.__call__, BaseHTTPMiddleware.__init__, BaseHTTPMiddleware.dispatch, _CachedRequest.__init__, _CachedRequest.wrapped_receive, _StreamingResponse.__call__; module: base
**cors.py** — class: CORSMiddleware; 13 imports; method: CORSMiddleware.__call__, CORSMiddleware.__init__, CORSMiddleware.allow_explicit_origin, CORSMiddleware.is_allowed_origin, CORSMiddleware.preflight_response, CORSMiddleware.send; module: cors
**errors.py** — class: ServerErrorMiddleware; 17 imports; method: ServerErrorMiddleware.__call__, ServerErrorMiddleware.__init__, ServerErrorMiddleware.debug_response, ServerErrorMiddleware.error_response, ServerErrorMiddleware.format_line, ServerErrorMiddleware.generate_frame_html; module: errors
**exceptions.py** — class: ExceptionMiddleware; 17 imports; method: ExceptionMiddleware.__call__, ExceptionMiddleware.__init__, ExceptionMiddleware.add_exception_handler, ExceptionMiddleware.http_exception, ExceptionMiddleware.websocket_exception; module: exceptions; rationale: [TODO] We ought to handle 404 cases if debug is set.
**gzip.py** — class: GZipMiddleware, GZipResponder, IdentityResponder; function: unattached_send; 10 imports; method: GZipMiddleware.__call__, GZipMiddleware.__init__, GZipResponder.__call__, GZipResponder.__init__, GZipResponder.apply_compression, IdentityResponder.__call__; module: gzip
**httpsredirect.py** — class: HTTPSRedirectMiddleware; 6 imports; method: HTTPSRedirectMiddleware.__call__, HTTPSRedirectMiddleware.__init__; module: httpsredirect
**sessions.py** — class: Session, SessionMiddleware; 16 imports; method: Session.__delitem__, Session.__setitem__, Session.clear, Session.mark_accessed, Session.mark_modified, Session.pop; module: sessions
**trustedhost.py** — class: TrustedHostMiddleware; 11 imports; method: TrustedHostMiddleware.__call__, TrustedHostMiddleware.__init__; module: trustedhost
**wsgi.py** — class: WSGIMiddleware, WSGIResponder; function: build_environ; 16 imports; method: WSGIMiddleware.__call__, WSGIMiddleware.__init__, WSGIResponder.__call__, WSGIResponder.__init__, WSGIResponder.sender, WSGIResponder.start_response; module: wsgi
**requests.py** — class: ClientDisconnect, HTTPConnection, Request; function: cookie_parser, empty_receive, empty_send; 36 imports; method: HTTPConnection.__getitem__, HTTPConnection.__init__, HTTPConnection.__iter__, HTTPConnection.__len__, HTTPConnection.app, HTTPConnection.auth; module: requests
**responses.py** — class: FileResponse, HTMLResponse, JSONResponse, MalformedRangeHeader, PlainTextResponse, RangeNotSatisfiable; 35 imports; method: FileResponse.__call__, FileResponse.__init__, FileResponse._handle_multiple_ranges, FileResponse._handle_simple, FileResponse._handle_single_range, FileResponse._parse_range_header; module: responses
**routing.py** — class: BaseRoute, Host, Match, Mount, NoMatchFound, Route; function: _wrap_gen_lifespan_context, compile_path, get_name, replace_params, request_response, websocket_session; 43 imports; method: BaseRoute.__call__, BaseRoute.handle, BaseRoute.matches, BaseRoute.url_path_for, Host.__eq__, Host.__init__; module: routing
**schemas.py** — class: BaseSchemaGenerator, EndpointInfo, OpenAPIResponse, SchemaGenerator; 13 imports; method: BaseSchemaGenerator.OpenAPIResponse, BaseSchemaGenerator._remove_converter, BaseSchemaGenerator.get_endpoints, BaseSchemaGenerator.get_schema, BaseSchemaGenerator.parse_docstring, OpenAPIResponse.render; module: schemas
**staticfiles.py** — class: NotModifiedResponse, StaticFiles; 19 imports; method: NotModifiedResponse.__init__, StaticFiles.__call__, StaticFiles.__init__, StaticFiles.check_config, StaticFiles.file_response, StaticFiles.get_directories; module: staticfiles
**status.py** — function: __dir__, __getattr__; 3 imports; module: status
**templating.py** — class: Jinja2Templates, _TemplateResponse; 16 imports; method: Jinja2Templates.TemplateResponse, Jinja2Templates.__init__, Jinja2Templates._setup_env_defaults, Jinja2Templates.get_template, _TemplateResponse.__call__, _TemplateResponse.__init__; module: templating
**testclient.py** — class: TestClient, WebSocketDenialResponse, WebSocketTestSession, _AsyncBackend, _TestClientTransport, _Upgrade; function: _is_asgi3; 42 imports; method: TestClient.__enter__, TestClient.__exit__, TestClient.__init__, TestClient._portal_factory, TestClient.delete, TestClient.get; module: testclient
**types.py** — 11 imports; module: types
**websockets.py** — class: WebSocket, WebSocketClose, WebSocketDisconnect, WebSocketState; 14 imports; method: WebSocket.__init__, WebSocket._raise_on_disconnect, WebSocket.accept, WebSocket.close, WebSocket.iter_bytes, WebSocket.iter_json; module: websockets
**texttable.py** — class: ArraySizeError, FallbackToText, Texttable; function: len, obj2unicode; 7 imports; method: ArraySizeError.__init__, ArraySizeError.__str__, Texttable.__init__, Texttable._build_hline, Texttable._check_align, Texttable._check_row_size; module: texttable
**typing_extensions.py** — class: _DefaultMixin, _EllipsisDummy, _ExtensionsSpecialForm, _SpecialForm, _TypeVarLikeMeta; function: IntVar, _caller, _concatenate_getitem, _create_concatenate_alias, _get_protocol_attrs, _has_generic_or_protocol_as_origin; 29 imports; method: _ExtensionsSpecialForm.__repr__, _SpecialForm.__call__, _SpecialForm.__getattr__, _SpecialForm.__getitem__, _SpecialForm.__init__, _SpecialForm.__instancecheck__; module: typing_extensions; rationale: [HACK] Arguments must be types, replace it with one., [NOTE] DO NOT call super() in any methods in this class, [TODO] Use inspect.VALUE here, and make the annotations lazily evaluated
**introspection.py** — class: AnnotationSource, ForbiddenQualifier, InspectedAnnotation, _UnknownTypeEnum; function: _literal_type_check, _unpack_annotated, _unpack_annotated_inner, get_literal_values, inspect_annotation; 17 imports; method: AnnotationSource.allowed_qualifiers, ForbiddenQualifier.__init__, _UnknownTypeEnum.__repr__, _UnknownTypeEnum.__str__; module: introspection; rationale: [NOTE] we could also check for generic aliases with a type alias as an origin.
**typing_objects.py** — function: _compile_identity_check_function, _compile_isinstance_check_function, is_namedtuple; 17 imports; module: typing_objects
**__init__.py** — 4 imports; module: __init__
**__main__.py** — 1 imports; module: __main__
**_compat.py** — 9 imports; module: _compat
**_subprocess.py** — function: get_subprocess, subprocess_started; 8 imports; module: _subprocess
**_types.py** — class: ASGI2Protocol, ASGIVersions, HTTPDisconnectEvent, HTTPRequestEvent, HTTPResponseBodyEvent, HTTPResponseDebugEvent; 13 imports; method: ASGI2Protocol.__call__, ASGI2Protocol.__init__; module: _types
**config.py** — class: Config; function: _normalize_dirs, create_ssl_context, is_dir, resolve_reload_patterns; 29 imports; method: Config.__init__, Config.asgi_version, Config.bind_socket, Config.configure_logging, Config.get_loop_factory, Config.is_ssl; module: config
**importer.py** — class: ImportFromStringError; function: import_from_string; 2 imports; module: importer
**off.py** — class: LifespanOff; 3 imports; method: LifespanOff.__init__, LifespanOff.shutdown, LifespanOff.startup; module: off
**on.py** — class: LifespanOn; 13 imports; method: LifespanOn.__init__, LifespanOn.main, LifespanOn.receive, LifespanOn.send, LifespanOn.shutdown, LifespanOn.startup; module: on
**logging.py** — class: AccessFormatter, ColourizedFormatter, DefaultFormatter; 7 imports; method: AccessFormatter.formatMessage, AccessFormatter.get_status_code, ColourizedFormatter.__init__, ColourizedFormatter.color_level_name, ColourizedFormatter.formatMessage, ColourizedFormatter.should_use_colors; module: logging
**asyncio.py** — function: asyncio_loop_factory; 4 imports; module: asyncio
**auto.py** — function: auto_loop_factory; 6 imports; module: auto
**uvloop.py** — function: uvloop_loop_factory; 4 imports; module: uvloop
**main.py** — function: __getattr__, _metavar_from_type, main, print_version, run; 31 imports; module: main
**asgi2.py** — class: ASGI2Middleware; 4 imports; method: ASGI2Middleware.__call__, ASGI2Middleware.__init__; module: asgi2
**message_logger.py** — class: MessageLoggerMiddleware; function: message_with_placeholders; 9 imports; method: MessageLoggerMiddleware.__call__, MessageLoggerMiddleware.__init__; module: message_logger
**proxy_headers.py** — class: ProxyHeadersMiddleware, _TrustedHosts; function: _parse_host_port, _parse_raw_hosts; 6 imports; method: ProxyHeadersMiddleware.__call__, ProxyHeadersMiddleware.__init__, _TrustedHosts.__contains__, _TrustedHosts.__init__, _TrustedHosts.get_trusted_client_address; module: proxy_headers; rationale: [NOTE] because we always convert invalid IP types to literals it, [NOTE] each proxy appends to the header list so check it in reverse order
**wsgi.py** — class: WSGIResponder, _WSGIMiddleware; function: build_environ; 21 imports; method: WSGIResponder.__call__, WSGIResponder.__init__, WSGIResponder.sender, WSGIResponder.start_response, WSGIResponder.wsgi, _WSGIMiddleware.__call__; module: wsgi
**auto.py** — 5 imports; module: auto
**flow_control.py** — class: FlowControl; function: service_unavailable; 4 imports; method: FlowControl.__init__, FlowControl.drain, FlowControl.pause_reading, FlowControl.pause_writing, FlowControl.resume_reading, FlowControl.resume_writing; module: flow_control
**h11_impl.py** — class: H11Protocol, RequestResponseCycle; function: _get_status_phrase; 31 imports; method: H11Protocol.__init__, H11Protocol._get_upgrade, H11Protocol._should_upgrade, H11Protocol._should_upgrade_to_ws, H11Protocol._unset_keepalive_if_required, H11Protocol._unsupported_upgrade_warning; module: h11_impl
**httptools_impl.py** — class: HttpToolsProtocol, RequestResponseCycle; function: _get_status_line; 31 imports; method: HttpToolsProtocol.__init__, HttpToolsProtocol._get_upgrade, HttpToolsProtocol._should_upgrade, HttpToolsProtocol._should_upgrade_to_ws, HttpToolsProtocol._start_asgi_task, HttpToolsProtocol._unset_keepalive_if_required; module: httptools_impl
**utils.py** — class: ClientDisconnected; function: get_client_addr, get_local_addr, get_path_with_query_string, get_remote_addr, is_ssl; 5 imports; module: utils
**auto.py** — 7 imports; module: auto
**websockets_impl.py** — class: Server, WebSocketProtocol; 33 imports; method: Server.is_serving, Server.register, Server.unregister, WebSocketProtocol.__init__, WebSocketProtocol.asgi_receive, WebSocketProtocol.asgi_send; module: websockets_impl
**websockets_sansio_impl.py** — class: WebSocketsSansIOProtocol; 34 imports; method: WebSocketsSansIOProtocol.__init__, WebSocketsSansIOProtocol.connection_lost, WebSocketsSansIOProtocol.connection_made, WebSocketsSansIOProtocol.data_received, WebSocketsSansIOProtocol.eof_received, WebSocketsSansIOProtocol.handle_bytes; module: websockets_sansio_impl
**wsproto_impl.py** — class: FrameTooLargeError, WSProtocol, WebsocketBuffer; 34 imports; method: WSProtocol.__init__, WSProtocol.connection_lost, WSProtocol.connection_made, WSProtocol.data_received, WSProtocol.eof_received, WSProtocol.handle_close; module: wsproto_impl; rationale: [TODO] Remove `type: ignore` when wsproto fixes the type annotation.
**server.py** — class: Server, ServerState; 28 imports; method: Server.__init__, Server._log_started_message, Server._serve, Server._wait_tasks_to_complete, Server.capture_signals, Server.handle_exit; module: server
**__init__.py** — 6 imports; module: __init__
**basereload.py** — class: BaseReload; function: _display_path; 14 imports; method: BaseReload.__init__, BaseReload.__iter__, BaseReload.__next__, BaseReload.pause, BaseReload.restart, BaseReload.run; module: basereload
**multiprocess.py** — class: Multiprocess, Process; 12 imports; method: Multiprocess.__init__, Multiprocess.handle_break, Multiprocess.handle_hup, Multiprocess.handle_int, Multiprocess.handle_signals, Multiprocess.handle_term; module: multiprocess
**statreload.py** — class: StatReload; 8 imports; method: StatReload.__init__, StatReload.iter_py_files, StatReload.restart, StatReload.should_restart; module: statreload
**watchfilesreload.py** — class: FileFilter, WatchFilesReload; 7 imports; method: FileFilter.__call__, FileFilter.__init__, WatchFilesReload.__init__, WatchFilesReload.should_restart; module: watchfilesreload
**workers.py** — class: UvicornH11Worker, UvicornWorker; 12 imports; method: UvicornWorker.__init__, UvicornWorker._install_sigquit_handler, UvicornWorker._serve, UvicornWorker.callback_notify, UvicornWorker.init_signals, UvicornWorker.run; module: workers
**events.py** — class: DirCreatedEvent, DirDeletedEvent, DirModifiedEvent, DirMovedEvent, FileClosedEvent, FileClosedNoWriteEvent; function: generate_sub_created_events, generate_sub_moved_events; 9 imports; method: FileSystemEventHandler.dispatch, FileSystemEventHandler.on_any_event, FileSystemEventHandler.on_closed, FileSystemEventHandler.on_closed_no_write, FileSystemEventHandler.on_created, FileSystemEventHandler.on_deleted; module: events
**__init__.py** — class: ObserverType; function: _get_observer_cls; 13 imports; method: ObserverType.__call__; module: __init__
**api.py** — class: BaseObserver, EventDispatcher, EventEmitter, EventQueue, ObservedWatch; 11 imports; method: BaseObserver.__init__, BaseObserver._add_emitter, BaseObserver._add_handler_for_watch, BaseObserver._clear_emitters, BaseObserver._remove_emitter, BaseObserver._remove_handlers_for_watch; module: api
**fsevents.py** — class: FSEventsEmitter, FSEventsObserver; 27 imports; method: FSEventsEmitter.__init__, FSEventsEmitter._encode_path, FSEventsEmitter._is_historic_created_event, FSEventsEmitter._is_meta_mod, FSEventsEmitter._is_recursive_event, FSEventsEmitter._queue_created_event; module: fsevents; rationale: [TODO] find out new path and generate DirMovedEvent?
**fsevents2.py** — class: FSEventsEmitter, FSEventsObserver2, FSEventsQueue, NativeEvent; 49 imports; method: FSEventsEmitter.__init__, FSEventsEmitter.on_thread_stop, FSEventsEmitter.queue_events, FSEventsObserver2.__init__, FSEventsQueue.__init__, FSEventsQueue._callback; module: fsevents2; rationale: [TODO] generate events for tree, [TODO] handle id wrapping
**inotify.py** — class: InotifyEmitter, InotifyFullEmitter, InotifyObserver; 27 imports; method: InotifyEmitter.__init__, InotifyEmitter._decode_path, InotifyEmitter.get_event_mask_from_filter, InotifyEmitter.on_thread_start, InotifyEmitter.on_thread_stop, InotifyEmitter.queue_events; module: inotify
**inotify_buffer.py** — class: InotifyBuffer; 6 imports; method: InotifyBuffer.__init__, InotifyBuffer._group_events, InotifyBuffer.close, InotifyBuffer.on_thread_stop, InotifyBuffer.read_event, InotifyBuffer.run; module: inotify_buffer; rationale: [XXX] Remove quotes after Python 3.9 drop
**inotify_c.py** — class: Inotify, InotifyConstants, InotifyEvent, InotifyEventStruct; 16 imports; method: Inotify.__init__, Inotify._add_dir_watch, Inotify._add_watch, Inotify._close_resources, Inotify._parse_event_buffer, Inotify._raise_error; module: inotify_c; rationale: [HACK] We need to traverse the directory path, [TODO] When a directory from another part of the
**kqueue.py** — class: KeventDescriptor, KeventDescriptorSet, KqueueEmitter, KqueueObserver; function: absolute_path, is_attrib_modified, is_deleted, is_modified, is_renamed; 32 imports; method: KeventDescriptor.__eq__, KeventDescriptor.__hash__, KeventDescriptor.__init__, KeventDescriptor.__ne__, KeventDescriptor.__repr__, KeventDescriptor.close; module: kqueue; rationale: [TODO] Do we need to fire moved events for the items, [TODO] We could simply ignore these files., [TODO] investigate why order appears to be reversed
**polling.py** — class: PollingEmitter, PollingObserver, PollingObserverVFS; 25 imports; method: PollingEmitter.__init__, PollingEmitter.on_thread_start, PollingEmitter.queue_events, PollingObserver.__init__, PollingObserverVFS.__init__; module: polling
**read_directory_changes.py** — class: WindowsApiEmitter, WindowsApiObserver; 28 imports; method: WindowsApiEmitter.__init__, WindowsApiEmitter._read_events, WindowsApiEmitter.on_thread_start, WindowsApiEmitter.on_thread_stop, WindowsApiEmitter.queue_events, WindowsApiObserver.__init__; module: read_directory_changes
**winapi.py** — class: FileNotifyInformation, OVERLAPPED, WinAPINativeEvent; function: _errcheck_bool, _errcheck_dword, _errcheck_handle, _generate_observed_path_deleted_event, _is_observed_path_deleted, _parse_event_buffer; 13 imports; method: WinAPINativeEvent.is_added, WinAPINativeEvent.is_modified, WinAPINativeEvent.is_removed, WinAPINativeEvent.is_removed_self, WinAPINativeEvent.is_renamed_new, WinAPINativeEvent.is_renamed_old; module: winapi; rationale: [NOTE] it will fail with ERROR_INVALID_PARAMETER when it is greater than 64 KB and
**__init__.py** — class: AutoRestartTrick, LoggerTrick, ShellCommandTrick, Trick; 18 imports; method: AutoRestartTrick.__init__, AutoRestartTrick._restart_process, AutoRestartTrick._start_process, AutoRestartTrick._stop_process, AutoRestartTrick.on_any_event, AutoRestartTrick.start; module: __init__; rationale: [FIXME] see issue #949, and find a way to better handle that scenario, [FIXME] see issue #949, and find a way to better handle that scenario
**__init__.py** — class: BaseThread, UnsupportedLibcError, WatchdogShutdownError; function: load_class, load_module; 6 imports; method: BaseThread.__init__, BaseThread.on_thread_start, BaseThread.on_thread_stop, BaseThread.should_keep_running, BaseThread.start, BaseThread.stop; module: __init__
**bricks.py** — class: SkipRepeatsQueue; 4 imports; method: SkipRepeatsQueue._get, SkipRepeatsQueue._init, SkipRepeatsQueue._put, SkipRepeatsQueue.put; module: bricks
**delayed_queue.py** — class: DelayedQueue; 7 imports; method: DelayedQueue.__init__, DelayedQueue.close, DelayedQueue.get, DelayedQueue.put, DelayedQueue.remove; module: delayed_queue
**dirsnapshot.py** — class: DirectorySnapshot, DirectorySnapshotDiff, EmptyDirectorySnapshot; 9 imports; method: DirectorySnapshot.__init__, DirectorySnapshot.__repr__, DirectorySnapshot.__str__, DirectorySnapshot.__sub__, DirectorySnapshot.inode, DirectorySnapshot.isdir; module: dirsnapshot
**echo.py** — function: echo, format_arg_value; 6 imports; module: echo
**event_debouncer.py** — class: EventDebouncer; 7 imports; method: EventDebouncer.__init__, EventDebouncer.handle_event, EventDebouncer.run, EventDebouncer.stop; module: event_debouncer
**patterns.py** — function: _match_path, filter_paths, match_any_paths; 5 imports; module: patterns
**platform.py** — function: get_platform_name, is_bsd, is_darwin, is_linux, is_windows; 2 imports; module: platform
**process_watcher.py** — class: ProcessWatcher; 6 imports; method: ProcessWatcher.__init__, ProcessWatcher.run; module: process_watcher
**version.py** — 1 imports; module: version
**watchmedo.py** — class: HelpFormatter, LogLevelError; function: _get_log_level_from_args, add_to_sys_path, argument, auto_restart, command, load_config; 34 imports; method: HelpFormatter.__init__, HelpFormatter.__repr__, HelpFormatter._split_lines; module: watchmedo
**__init__.py** — 63 imports; module: __init__
**__main__.py** — 1 imports; module: __main__
**async_timeout.py** — class: Timeout, _State; function: timeout, timeout_at; 8 imports; method: Timeout.__aenter__, Timeout.__aexit__, Timeout.__enter__, Timeout.__exit__, Timeout.__init__, Timeout._do_enter; module: async_timeout
**client.py** — class: ClientConnection, HTTPProxyConnection, connect; function: connect_http_proxy, process_exception, unix_connect; 47 imports; method: ClientConnection.__init__, ClientConnection.handshake, ClientConnection.process_event, HTTPProxyConnection.__init__, HTTPProxyConnection.connection_lost, HTTPProxyConnection.connection_made; module: client
**compatibility.py** — 7 imports; module: compatibility
**connection.py** — class: Connection; function: broadcast; 46 imports; method: Connection.__aenter__, Connection.__aexit__, Connection.__aiter__, Connection.__init__, Connection.acknowledge_pings, Connection.close; module: connection
**messages.py** — class: Assembler, SimpleQueue; 18 imports; method: Assembler.__init__, Assembler.close, Assembler.get, Assembler.get_iter, Assembler.maybe_pause, Assembler.maybe_resume; module: messages
**router.py** — class: Router; 16 imports; method: Router.__init__, Router.get_server_name, Router.handler, Router.not_found, Router.redirect, Router.route_request; module: router
**server.py** — class: Server, ServerConnection, serve; function: basic_auth, is_credentials, unix_serve; 38 imports; method: Server.__aenter__, Server.__aexit__, Server.__init__, Server._close, Server.close, Server.conn_handler; module: server
**auth.py** — 4 imports; module: auth
**cli.py** — class: ReadLines; function: interactive_client, main, print_during_input, print_incoming_messages, print_over_input, send_outgoing_messages; 14 imports; method: ReadLines.__init__, ReadLines.connection_lost, ReadLines.connection_made, ReadLines.data_received, ReadLines.eof_received, ReadLines.parse; module: cli
**client.py** — class: ClientConnection, ClientProtocol; function: backoff; 43 imports; method: ClientConnection.__init__, ClientProtocol.__init__, ClientProtocol.connect, ClientProtocol.parse, ClientProtocol.process_extensions, ClientProtocol.process_response; module: client
**connection.py** — 6 imports; module: connection
**datastructures.py** — class: Headers, MultipleValuesError, SupportsKeysAndGetItem; 7 imports; method: Headers.__contains__, Headers.__delitem__, Headers.__eq__, Headers.__getitem__, Headers.__init__, Headers.__iter__; module: datastructures
**exceptions.py** — class: ConcurrencyError, ConnectionClosed, ConnectionClosedError, ConnectionClosedOK, DuplicateParameter, InvalidHandshake; 5 imports; method: ConnectionClosed.__init__, ConnectionClosed.__str__, ConnectionClosed.code, ConnectionClosed.reason, DuplicateParameter.__init__, DuplicateParameter.__str__; module: exceptions
**__init__.py** — 1 imports; module: __init__
**base.py** — class: ClientExtensionFactory, Extension, ServerExtensionFactory; 5 imports; method: ClientExtensionFactory.get_request_params, ClientExtensionFactory.process_response_params, Extension.decode, Extension.encode, ServerExtensionFactory.process_request_params; module: base
**permessage_deflate.py** — class: ClientPerMessageDeflateFactory, PerMessageDeflate, ServerPerMessageDeflateFactory; function: _build_parameters, _extract_parameters, enable_client_permessage_deflate, enable_server_permessage_deflate; 18 imports; method: ClientPerMessageDeflateFactory.__init__, ClientPerMessageDeflateFactory.get_request_params, ClientPerMessageDeflateFactory.process_response_params, PerMessageDeflate.__init__, PerMessageDeflate.__repr__, PerMessageDeflate.decode; module: permessage_deflate
**frames.py** — class: Close, CloseCode, Frame, Opcode; 16 imports; method: Close.__str__, Close.check, Close.parse, Close.serialize, Frame.__str__, Frame.check; module: frames
**headers.py** — function: build_authorization_basic, build_extension, build_extension_item, build_host, build_quoted_string, build_subprotocol; 17 imports; module: headers
**http.py** — 6 imports; module: http
**http11.py** — class: Request, Response; function: d, parse_headers, parse_line, read_body; 11 imports; method: Request.exception, Request.parse, Request.serialize, Response.exception, Response.parse, Response.serialize; module: http11
**imports.py** — function: import_name, lazy_import; 4 imports; module: imports
**__init__.py** — 2 imports; module: __init__
**auth.py** — class: BasicAuthWebSocketServerProtocol; function: basic_auth_protocol_factory, is_credentials; 15 imports; method: BasicAuthWebSocketServerProtocol.__init__, BasicAuthWebSocketServerProtocol.check_credentials, BasicAuthWebSocketServerProtocol.process_request; module: auth
**client.py** — class: Connect, WebSocketClientProtocol; function: unix_connect; 47 imports; method: Connect.__aenter__, Connect.__aexit__, Connect.__aiter__, Connect.__await__, Connect.__await_impl__, Connect.__init__; module: client
**exceptions.py** — class: AbortHandshake, InvalidStatusCode, RedirectHandshake; 6 imports; method: AbortHandshake.__init__, AbortHandshake.__str__, InvalidStatusCode.__init__, InvalidStatusCode.__str__, RedirectHandshake.__init__, RedirectHandshake.__str__; module: exceptions
**framing.py** — class: Frame; function: parse_close, prepare_ctrl, prepare_data, serialize_close; 16 imports; method: Frame.__str__, Frame.check, Frame.new_frame, Frame.read, Frame.write; module: framing
**handshake.py** — function: build_request, build_response, check_request, check_response; 14 imports; module: handshake
**http.py** — function: d, read_headers, read_line, read_request, read_response; 6 imports; module: http
**protocol.py** — class: WebSocketCommonProtocol; function: broadcast; 50 imports; method: WebSocketCommonProtocol.__aiter__, WebSocketCommonProtocol.__init__, WebSocketCommonProtocol._drain, WebSocketCommonProtocol._drain_helper, WebSocketCommonProtocol.abort_pings, WebSocketCommonProtocol.close; module: protocol
**server.py** — class: Serve, WebSocketServer, WebSocketServerProtocol; function: remove_path_argument, unix_serve; 47 imports; method: Serve.__aenter__, Serve.__aexit__, Serve.__await__, Serve.__await_impl__, Serve.__init__, WebSocketServer.__aenter__; module: server
**protocol.py** — class: Protocol, Side, State; 29 imports; method: Protocol.__init__, Protocol.close_code, Protocol.close_exc, Protocol.close_expected, Protocol.close_reason, Protocol.data_to_send; module: protocol
**proxy.py** — class: Proxy; function: get_proxy, parse_proxy, prepare_connect_request; 11 imports; method: Proxy.user_info; module: proxy
**server.py** — class: ServerConnection, ServerProtocol; 44 imports; method: ServerConnection.__init__, ServerProtocol.__init__, ServerProtocol.accept, ServerProtocol.parse, ServerProtocol.process_extensions, ServerProtocol.process_origin; module: server
**speedups.c** — module: speedups
**streams.py** — class: StreamReader; 2 imports; method: StreamReader.__init__, StreamReader.at_eof, StreamReader.discard, StreamReader.feed_data, StreamReader.feed_eof, StreamReader.read_exact; module: streams
**client.py** — class: ClientConnection, SSLSSLSocket; function: connect, connect_http_proxy, read_connect_response, unix_connect; 38 imports; method: ClientConnection.__init__, ClientConnection.handshake, ClientConnection.process_event, ClientConnection.recv_events, SSLSSLSocket.__getattr__, SSLSSLSocket.__init__; module: client
**connection.py** — class: Connection; 38 imports; method: Connection.__enter__, Connection.__exit__, Connection.__init__, Connection.__iter__, Connection.acknowledge_pings, Connection.close; module: connection
**messages.py** — class: Assembler; 17 imports; method: Assembler.__init__, Assembler.close, Assembler.get, Assembler.get_iter, Assembler.get_next_frame, Assembler.maybe_pause; module: messages
**router.py** — class: Router; 15 imports; method: Router.__init__, Router.get_server_name, Router.handler, Router.not_found, Router.redirect, Router.route_request; module: router
**server.py** — class: Server, ServerConnection; function: __getattr__, basic_auth, is_credentials, serve, unix_serve; 39 imports; method: Server.__enter__, Server.__exit__, Server.__init__, Server.fileno, Server.serve_forever, Server.shutdown; module: server
**utils.py** — class: Deadline; 2 imports; method: Deadline.__init__, Deadline.timeout; module: utils
**typing.py** — 7 imports; module: typing
**uri.py** — class: WebSocketURI; function: parse_uri; 4 imports; method: WebSocketURI.resource_name, WebSocketURI.user_info; module: uri
**utils.py** — function: accept_key, apply_mask, generate_key; 6 imports; module: utils
**version.py** — 5 imports; module: version
**BackupRead_BackupWrite.py** — 8 imports; module: BackupRead_BackupWrite
**BackupSeek_streamheaders.py** — function: parse_stream_header; 7 imports; module: BackupSeek_streamheaders
**CopyFileEx.py** — function: ProgressRoutine; 2 imports; module: CopyFileEx
**CreateFileTransacted_MiniVersion.py** — function: demo; 8 imports; module: CreateFileTransacted_MiniVersion
**EvtFormatMessage.py** — function: main; 2 imports; module: EvtFormatMessage
**EvtSubscribe_pull.py** — 3 imports; module: EvtSubscribe_pull
**EvtSubscribe_push.py** — function: c; 3 imports; module: EvtSubscribe_push
**FileSecurityTest.py** — 6 imports; module: FileSecurityTest
**GetSaveFileName.py** — 3 imports; module: GetSaveFileName
**NetValidatePasswordPolicy.py** — function: main; 6 imports; module: NetValidatePasswordPolicy
**OpenEncryptedFileRaw.py** — function: ReadCallback, WriteCallback; 4 imports; module: OpenEncryptedFileRaw
**RegCreateKeyTransacted.py** — 3 imports; module: RegCreateKeyTransacted
**RegRestoreKey.py** — 6 imports; module: RegRestoreKey
**SystemParametersInfo.py** — 6 imports; module: SystemParametersInfo
**setup.py** — 4 imports; module: setup
**ddeclient.py** — 2 imports; module: ddeclient
**ddeserver.py** — class: MyOtherTopic, MyRequestTopic, MySystemTopic; 3 imports; method: MyOtherTopic.Exec, MyOtherTopic.__init__, MyRequestTopic.Request, MyRequestTopic.__init__, MySystemTopic.Exec, MySystemTopic.__init__; module: ddeserver
**desktopmanager.py** — function: create_desktop, desktop_name_dlgproc, get_new_desktop_name, icon_wndproc, new_icon; 10 imports; module: desktopmanager
**eventLogDemo.py** — function: ReadLog, test, usage; 7 imports; module: eventLogDemo
**getfilever.py** — 2 imports; module: getfilever
**mmapfile_demo.py** — 5 imports; module: mmapfile_demo
**cat.py** — 1 imports; module: cat
**runproc.py** — class: Process; 8 imports; method: Process.run; module: runproc
**print_desktop.py** — 5 imports; module: print_desktop
**rastest.py** — function: Callback, Connect, Disconnect, EditEntry, HangUp, ShowConnections; 5 imports; module: rastest
**GetTokenInformation.py** — function: dump_token; 8 imports; module: GetTokenInformation
**account_rights.py** — 4 imports; module: account_rights
**explicit_entries.py** — 9 imports; module: explicit_entries
**get_policy_info.py** — 1 imports; module: get_policy_info
**list_rights.py** — 4 imports; module: list_rights
**localized_names.py** — function: LookupAliasFromRid, LookupUserGroupFromRid, main; 8 imports; module: localized_names; rationale: [NOTE] if you were looking up multiple sids based on the same
**lsaregevent.py** — 2 imports; module: lsaregevent
**lsastore.py** — 1 imports; module: lsastore
**query_information.py** — function: GetDomainName; 5 imports; module: query_information
**regsave_sa.py** — 6 imports; module: regsave_sa
**regsecurity.py** — 4 imports; module: regsecurity
**sa_inherit.py** — 2 imports; module: sa_inherit
**security_enums.py** — class: Enum; 3 imports; method: Enum.__init__, Enum.lookup_flags, Enum.lookup_name; module: security_enums
**set_file_audit.py** — 14 imports; module: set_file_audit
**set_file_owner.py** — 4 imports; module: set_file_owner
**set_policy_info.py** — 1 imports; module: set_policy_info
**setkernelobjectsecurity.py** — 3 imports; module: setkernelobjectsecurity
**setnamedsecurityinfo.py** — 4 imports; module: setnamedsecurityinfo
**setsecurityinfo.py** — 3 imports; module: setsecurityinfo
**setuserobjectsecurity.py** — 3 imports; module: setuserobjectsecurity
**fetch_url.py** — function: open_url; 8 imports; module: fetch_url
**simple_auth.py** — function: lookup_ret_code; 4 imports; module: simple_auth
**socket_server.py** — class: SSPISocketServer; function: GetUserName, _get_msg, _send_msg, serve, sspi_client; 7 imports; method: SSPISocketServer.__init__, SSPISocketServer.process_request, SSPISocketServer.verify_request; module: socket_server
**validate_password.py** — function: validate; 4 imports; module: validate_password
**nativePipeTestService.py** — class: NativeTestPipeService; function: main; 7 imports; module: nativePipeTestService
**pipeTestService.py** — class: TestPipeService; function: ApplyIgnoreError; 13 imports; method: TestPipeService.CreatePipeSecurityObject, TestPipeService.DoProcessClient, TestPipeService.ProcessClient, TestPipeService.SvcDoRun, TestPipeService.SvcStop, TestPipeService.__init__; module: pipeTestService
**pipeTestServiceClient.py** — function: CallPipe, main, stressTestClient, stressThread, testClient, testLargeMessage; 11 imports; module: pipeTestServiceClient
**serviceEvents.py** — class: EventDemoService; 7 imports; method: EventDemoService.GetAcceptedControls, EventDemoService.SvcDoRun, EventDemoService.SvcOtherEx, EventDemoService.SvcStop, EventDemoService.__init__; module: serviceEvents
**timer_demo.py** — class: glork; function: demo; 4 imports; method: glork.__init__, glork.increment; module: timer_demo
**win32clipboardDemo.py** — class: Foo; function: TestClipboardEnum, TestCustomFormat, TestEmptyClipboard, TestText; 12 imports; method: Foo.__eq__, Foo.__init__, Foo.__lt__; module: win32clipboardDemo
**win32clipboard_bitmapdemo.py** — class: ViewerWindow; 4 imports; method: ViewerWindow.OnChangeCBChain, ViewerWindow.OnClose, ViewerWindow.OnCreate, ViewerWindow.OnDrawClipboard, ViewerWindow.OnPaint, ViewerWindow.__init__; module: win32clipboard_bitmapdemo
**win32comport_demo.py** — class: SerialTTY; function: FindModem; 32 imports; method: SerialTTY.Run, SerialTTY._ComPortThread, SerialTTY._UserInputReaderThread, SerialTTY.__init__; module: win32comport_demo
**win32console_demo.py** — 3 imports; module: win32console_demo
**win32cred_demo.py** — 6 imports; module: win32cred_demo
**win32fileDemo.py** — function: SimpleFileDemo; 4 imports; module: win32fileDemo
**win32gui_demo.py** — function: OnPaint_1, OnPaint_2, TestEnumWindows, TestGradientFill, TestSetWorldTransform, _MyCallback; 6 imports; module: win32gui_demo
**win32gui_devicenotify.py** — function: OnDeviceChange, TestDeviceNotifications; 7 imports; module: win32gui_devicenotify
**win32gui_dialog.py** — class: DemoDialog, DemoWindow, DemoWindowBase, LVCOLUMN, LVITEM, _WIN32MASKEDSTRUCT; function: DemoCreateWindow, DemoModal; 12 imports; method: DemoDialog.DoModal, DemoDialog.OnClose, DemoWindow.CreateWindow, DemoWindow.OnClose, DemoWindow.OnDestroy, DemoWindowBase.AddListItem; module: win32gui_dialog; rationale: [NOTE] See the win32gui_struct module for an alternative way of dealing
**win32gui_menu.py** — class: MainWindow; function: main; 59 imports; method: MainWindow.OnCommand, MainWindow.OnDestroy, MainWindow.OnDrawItem, MainWindow.OnMeasureItem, MainWindow.OnTaskbarNotify, MainWindow.__init__; module: win32gui_menu; rationale: [NOTE] This is a work in progress.  Todo:
**win32gui_taskbar.py** — class: MainWindow; function: main; 7 imports; method: MainWindow.OnCommand, MainWindow.OnDestroy, MainWindow.OnRestart, MainWindow.OnTaskbarNotify, MainWindow._DoCreateIcons, MainWindow.__init__; module: win32gui_taskbar
**win32netdemo.py** — function: CreateUser, GetInfo, GroupEnum, LocalGroup, LocalGroupEnum, ServerEnum; 9 imports; module: win32netdemo
**win32rcparser_demo.py** — class: DemoWindow; function: DemoModal; 6 imports; method: DemoWindow.CreateWindow, DemoWindow.DoModal, DemoWindow.OnClose, DemoWindow.OnCommand, DemoWindow.OnDestroy, DemoWindow.OnInitDialog; module: win32rcparser_demo
**win32servicedemo.py** — function: EnumServices; 2 imports; module: win32servicedemo
**win32ts_logoff_disconnected.py** — 3 imports; module: win32ts_logoff_disconnected
**testwnet.py** — function: TestConnection, TestGetUser, TestOpenEnum, _doDumpHandle, findUnusedDriveLetter; 4 imports; module: testwnet
**winnetwk.py** — module: winnetwk
**winprocess.py** — class: Process; function: logonUser, run; 9 imports; method: Process.__close__, Process.__init__, Process.exitCode, Process.kill, Process.wait; module: winprocess
**_win32verstamp_pywin32ctypes.py** — function: BeginUpdateResource, EndUpdateResource, UpdateResource, check_false, check_null, make_error; 17 imports; module: _win32verstamp_pywin32ctypes
**afxres.py** — 2 imports; module: afxres
**commctrl.py** — function: INDEXTOOVERLAYMASK, INDEXTOSTATEIMAGEMASK; module: commctrl
**mmsystem.py** — function: DIBINDEX, MCI_HMS_HOUR, MCI_HMS_MINUTE, MCI_HMS_SECOND, MCI_MSF_FRAME, MCI_MSF_MINUTE; 1 imports; module: mmsystem
**netbios.py** — class: NCBStruct; function: ACTION_HEADER, ADAPTER_STATUS, FIND_NAME_BUFFER, FIND_NAME_HEADER, LANA_ENUM, NAME_BUFFER; 4 imports; method: NCBStruct.__init__, NCBStruct.__setattr__, NCBStruct._pack, NCBStruct._unpack; module: netbios
**ntsecuritycon.py** — module: ntsecuritycon
**pywin32_bootstrap.py** — 2 imports; module: pywin32_bootstrap
**pywin32_testutil.py** — class: LeakTestCase, TestLoader, TestProgram, TestResult, TestRunner; function: find_test_fixture, testmain; 14 imports; method: LeakTestCase.__call__, LeakTestCase.__init__, LeakTestCase._do_leak_tests, LeakTestCase.countTestCases, LeakTestCase.runTest, TestLoader._getTestWrapper; module: pywin32_testutil
**pywintypes.py** — function: __import_pywin32_system_module__; 8 imports; module: pywintypes
**rasutil.py** — function: TestCallback, test; 1 imports; module: rasutil
**regcheck.py** — function: CheckHelpFiles, CheckPathString, CheckPythonPaths, CheckRegisteredExe, CheckRegisteredModules, CheckRegistry; 7 imports; module: regcheck
**regutil.py** — function: BuildDefaultPythonKey, GetAppPathsKey, GetRegisteredExe, GetRegisteredHelpFile, GetRegisteredNamedPath, GetRegistryDefaultValue; 5 imports; module: regutil
**sspi.py** — class: ClientAuth, ServerAuth, _BaseAuth; 2 imports; method: ClientAuth.__init__, ClientAuth.authorize, ServerAuth.__init__, ServerAuth.authorize, _BaseAuth.__init__, _BaseAuth._amend_ctx_name; module: sspi
**sspicon.py** — function: SEC_SUCCESS; module: sspicon
**win2kras.py** — 2 imports; module: win2kras
**win32con.py** — function: GetBValue, GetGValue, GetRValue, IMAGE_ORDINAL, IMAGE_SNAP_BY_ORDINAL, PALETTEINDEX; module: win32con
**win32cryptcon.py** — function: GET_ALG_CLASS, GET_ALG_SID, GET_ALG_TYPE, GET_CERT_ENCODING_TYPE, GET_CMSG_ENCODING_TYPE, RCRYPT_FAILED; module: win32cryptcon
**win32evtlogutil.py** — function: AddSourceToRegistry, FeedEventLogRecords, FormatMessage, RemoveSourceFromRegistry, ReportEvent, SafeFormatMessage; 4 imports; module: win32evtlogutil
**win32gui_struct.py** — class: DEV_BROADCAST_INFO; function: EmptyLVCOLUMN, EmptyLVITEM, EmptyMENUINFO, EmptyMENUITEMINFO, EmptyTVITEM, PackDEV_BROADCAST; 9 imports; method: DEV_BROADCAST_INFO.__init__, DEV_BROADCAST_INFO.__str__; module: win32gui_struct; rationale: [NOTE] I considered making these structures look like real classes, and, [NOTE] No MIIM_TYPE - this used to screw win2k/98., [TODO] Dynamic namedtuple. This could be made static, also exposing the types
**win32inetcon.py** — module: win32inetcon
**win32netcon.py** — module: win32netcon
**win32pdhquery.py** — class: BaseQuery, Query, QueryError; 5 imports; method: BaseQuery.__getinitargs__, BaseQuery.__init__, BaseQuery.addcounter, BaseQuery.addcounterbybrowsing, BaseQuery.close, BaseQuery.collectdata; module: win32pdhquery
**win32pdhutil.py** — function: BrowseCallBackDemo, FindPerformanceAttributesByName, GetPerformanceAttributes, ShowAllProcesses, browse, find_pdh_counter_localized_name; 5 imports; module: win32pdhutil; rationale: [NOTE] Many counters require 2 samples to give accurate results,, [NOTE] This BrowseCallback doesn't seem to work on Vista for markh.
**win32rcparser.py** — class: ControlDef, DialogDef, RCParser, StringDef; function: GenerateFrozenResource, Parse, ParseStreams; 8 imports; method: ControlDef.__init__, ControlDef.createDialogTemplate, ControlDef.toString, DialogDef.__init__, DialogDef.createDialogTemplate, RCParser.__init__; module: win32rcparser
**win32serviceutil.py** — class: ServiceFramework; function: ChangeServiceConfig, ControlService, DebugService, GetServiceClassString, GetServiceCustomOption, HandleCommandLine; 14 imports; method: ServiceFramework.GetAcceptedControls, ServiceFramework.ReportServiceStatus, ServiceFramework.ServiceCtrlHandler, ServiceFramework.ServiceCtrlHandlerEx, ServiceFramework.SvcInterrogate, ServiceFramework.SvcOther; module: win32serviceutil
**win32timezone.py** — class: DLLHandleCache, DYNAMIC_TIME_ZONE_INFORMATION, RangeMap, SYSTEMTIME, TIME_ZONE_INFORMATION, TimeZoneDefinition; function: GetTZCapabilities, now, resolveMUITimeZone, utcnow; 22 imports; method: DLLHandleCache.__getitem__, DLLHandleCache.__init__, RangeMap.__getitem__, RangeMap.__init__, RangeMap._find_first_match_, RangeMap.bounds; module: win32timezone
**win32traceutil.py** — function: RunAsCollector, SetupForPrint; 3 imports; module: win32traceutil
**win32verstamp.py** — function: String, StringFileInfo, StringTable, VS_FIXEDFILEINFO, VS_VERSION_INFO, Var; 7 imports; module: win32verstamp
**winerror.py** — function: FAILED, FILTER_HRESULT_FROM_FLT_NTSTATUS, GetScode, HRESULT_CODE, HRESULT_FACILITY, HRESULT_FROM_NT; 1 imports; module: winerror
**winioctlcon.py** — function: CTL_CODE, DEVICE_TYPE_FROM_CTL_CODE; 3 imports; module: winioctlcon
**winnt.py** — function: BTYPE, DECREF, IMAGE_ORDINAL, IMAGE_SNAP_BY_ORDINAL, INCREF, ISARY; module: winnt
**winperf.py** — module: winperf
**winxptheme.py** — 1 imports; module: winxptheme
**ControlService.py** — class: ServiceDlg, StartupDlg; 5 imports; method: ServiceDlg.GetResource, ServiceDlg.GetSelService, ServiceDlg.OnContinueCmd, ServiceDlg.OnInitDialog, ServiceDlg.OnListEvent, ServiceDlg.OnPauseCmd; module: ControlService
**BrandProject.py** — function: BrandProject, usage; 6 imports; module: BrandProject
**bulkstamp.py** — function: load_descriptions, scan, walk; 7 imports; module: bulkstamp
**vssutil.py** — function: CountCheckouts, GetLastBuildNo, GetSS, MakeNewBuildNo, SubstituteInFile, SubstituteInString; 9 imports; module: vssutil
**backupEventLog.py** — function: BackupClearLog; 4 imports; module: backupEventLog
**h2py.py** — function: main, process, pytify; 6 imports; module: h2py
**killProcName.py** — function: killProcName; 4 imports; module: killProcName
**pywin32_postinstall.py** — class: Tee; function: CopyTo, LoadSystemModule, RegisterCOMObjects, RegisterHelpFile, RegisterPythonwin, SetPyKeyVal; 19 imports; method: Tee.__init__, Tee.flush, Tee.write; module: pywin32_postinstall; rationale: [NOTE] This used to be run from inside the bdist_wininst created binary un/installer.
**pywin32_testall.py** — function: find_and_run, main, run_test; 5 imports; module: pywin32_testall
**rasutil.py** — class: ConnectionError; function: Connect, Disconnect, Usage; 4 imports; module: rasutil
**regsetup.py** — class: error; function: FileExists, FindAppPath, FindHelpPath, FindPackagePath, FindPythonExe, FindRegisterApp; 9 imports; module: regsetup
**setup_d.py** — function: _docopy, _domodule, _doregister, usage_and_die; 7 imports; module: setup_d
**handles.py** — class: Cycle, PyHandleTestCase, TestError1, TestError2; 6 imports; method: Cycle.__init__, PyHandleTestCase.testCleanup1, PyHandleTestCase.testCleanup2, PyHandleTestCase.testCleanup3, PyHandleTestCase.testCleanupGood, PyHandleTestCase.testGC; module: handles
**test_clipboard.py** — class: CrashingTestCase, TestBitmap, TestGlobalMemory, TestStrings; 17 imports; method: CrashingTestCase.test_722082, TestBitmap.setUp, TestBitmap.tearDown, TestBitmap.test_bitmap_roundtrip, TestGlobalMemory.setUp, TestGlobalMemory.tearDown; module: test_clipboard
**test_exceptions.py** — class: TestAPISimple, TestBase, TestCOMSimple; 5 imports; method: TestAPISimple._getInvalidHandleException, TestAPISimple.testAsStr, TestAPISimple.testAsTuple, TestAPISimple.testAttributes, TestAPISimple.testBaseClass, TestAPISimple.testClassName; module: test_exceptions
**test_odbc.py** — class: TestStuff; 9 imports; method: TestStuff._test_val, TestStuff.setUp, TestStuff.tearDown, TestStuff.testBit, TestStuff.testDates, TestStuff.testFloat; module: test_odbc
**test_pywintypes.py** — class: TestCase; 5 imports; method: TestCase.testGUID, TestCase.testGUIDInDict, TestCase.testGUIDRichCmp, TestCase.testPyTimeCompare, TestCase.testPyTimeCompareOther, TestCase.testPyTimeFormat; module: test_pywintypes
**test_security.py** — class: DomainTests, SecurityTests, TestDS, TestTranslate; 8 imports; method: DomainTests.setUp, DomainTests.tearDown, SecurityTests.setUp, SecurityTests.tearDown, SecurityTests.testBuffer, SecurityTests.testEqual; module: test_security
**test_sspi.py** — class: TestSSPI; function: applyHandlingSkips; 6 imports; method: TestSSPI._doAuth, TestSSPI._doTestEncrypt, TestSSPI._doTestEncryptStream, TestSSPI._doTestImpersonate, TestSSPI._doTestSign, TestSSPI._testSequenceEncrypt; module: test_sspi
**test_win32api.py** — class: CurrentUserTestCase, FileNames, FormatMessage, Misc, Registry, TestError; 11 imports; method: CurrentUserTestCase.testGetCurrentUser, FileNames.testLongLongPathNames, FileNames.testShortLongPathNames, FileNames.testShortUnicodeNames, FormatMessage.test_FromString, Misc.testGetSystemCpuSetInformation; module: test_win32api
**test_win32clipboard.py** — class: TestGetSetClipboardData; 2 imports; method: TestGetSetClipboardData.copyData, TestGetSetClipboardData.copyText, TestGetSetClipboardData.test_data, TestGetSetClipboardData.test_text; module: test_win32clipboard
**test_win32cred.py** — class: TestCredFunctions; 5 imports; method: TestCredFunctions.create_dummy_cred, TestCredFunctions.is_dummy_cred, TestCredFunctions.setUp, TestCredFunctions.test_creddelete, TestCredFunctions.test_credgetsessiontypes; module: test_win32cred
**test_win32crypt.py** — class: Crypt, TestCerts; function: open_windows_certstore; 18 imports; method: Crypt.testEntropy, Crypt.testSimple, TestCerts.checkCertFile, TestCerts.readCertFile, TestCerts.testCertBase64, TestCerts.testCertBinary; module: test_win32crypt
**test_win32event.py** — class: TestEvent, TestMutex, TestWaitFunctions, TestWaitableTimer; 3 imports; method: TestEvent.assertNotSignaled, TestEvent.assertSignaled, TestEvent.testCreateEvent, TestEvent.testResetEvent, TestEvent.testSetEvent, TestMutex.testReleaseMutex; module: test_win32event
**test_win32file.py** — class: TestConnect, TestDirectoryChanges, TestEncrypt, TestFindFiles, TestGetFileInfoByHandleEx, TestOverlapped; 21 imports; method: TestConnect.connect_thread_runner, TestConnect.test_connect_with_payload, TestConnect.test_connect_without_payload, TestDirectoryChanges._watcherThread, TestDirectoryChanges._watcherThreadOverlapped, TestDirectoryChanges.setUp; module: test_win32file; rationale: [NOTE] previously used shutil.rmtree, but when looking for
**test_win32gui.py** — class: TestEnumWindowsFamily, TestPyGetMemory, TestPyGetString, TestWindowProperties; 7 imports; method: TestEnumWindowsFamily.enum_callback, TestEnumWindowsFamily.enum_callback_exc, TestEnumWindowsFamily.enum_callback_sle, TestEnumWindowsFamily.setUp, TestEnumWindowsFamily.test_enumchildwindows, TestEnumWindowsFamily.test_enumdesktopwindows; module: test_win32gui
**test_win32guistruct.py** — class: TestBase, TestDEV_BROADCAST_DEVICEINTERFACE, TestDEV_BROADCAST_HANDLE, TestDEV_BROADCAST_VOLUME, TestLVColumn, TestListViewItem; 5 imports; method: TestBase.assertDictEquals, TestDEV_BROADCAST_DEVICEINTERFACE.testPackUnpack, TestDEV_BROADCAST_HANDLE.testGUID, TestDEV_BROADCAST_HANDLE.testPackUnpack, TestDEV_BROADCAST_VOLUME.testPackUnpack, TestLVColumn._testPackUnpack; module: test_win32guistruct
**test_win32inet.py** — class: CookieTests, TestNetwork, UrlTests; 18 imports; method: CookieTests.testCookies, CookieTests.testCookiesEmpty, TestNetwork.setUp, TestNetwork.tearDown, TestNetwork.testFtpCommand, TestNetwork.testPythonDotOrg; module: test_win32inet
**test_win32net.py** — class: TestCase; 2 imports; method: TestCase.testGroupsBadResume, TestCase.testGroupsGoodResume; module: test_win32net
**test_win32pipe.py** — class: PipeTests; 9 imports; method: PipeTests._serverThread, PipeTests.startPipeServer, PipeTests.testCallNamedPipe, PipeTests.testTransactNamedPipeAsync, PipeTests.testTransactNamedPipeBlocking, PipeTests.testTransactNamedPipeBlockingBuffer; module: test_win32pipe
**test_win32print.py** — class: Win32PrintTestCase; 2 imports; method: Win32PrintTestCase.setUp, Win32PrintTestCase.test_printer_levels_read_dummy; module: test_win32print
**test_win32profile.py** — class: Tester; 3 imports; method: Tester.test_environment; module: test_win32profile
**test_win32rcparser.py** — class: TestGenerated, TestParser; 5 imports; method: TestGenerated.setUp, TestParser.setUp, TestParser.testStandardIds, TestParser.testStrings, TestParser.testTabStop; module: test_win32rcparser
**test_win32timezone.py** — class: Win32TimeZoneTest; 3 imports; method: Win32TimeZoneTest.testWin32TZ; module: test_win32timezone
**test_win32trace.py** — class: BasicSetupTearDown, TestHugeChunks, TestInitOps, TestModuleOps, TestMultipleThreadsWriting, TestOutofProcess; function: CheckNoOtherReaders, SkipIfCI, _RunAsTestProcess; 8 imports; method: BasicSetupTearDown.setUp, BasicSetupTearDown.tearDown, TestHugeChunks.setUp, TestHugeChunks.tearDown, TestHugeChunks.testHugeChunks, TestInitOps.setUp; module: test_win32trace
**test_win32ts.py** — class: Win32TsTestCase; 2 imports; method: Win32TsTestCase.test_is_remote_session; module: test_win32ts
**test_win32wnet.py** — class: TestCase; 4 imports; method: TestCase._checkItemAttributes, TestCase.findUnusedDriveLetter, TestCase.iterConnectableShares, TestCase.testAddConnection, TestCase.testAddConnectionOld, TestCase.testGetUser; module: test_win32wnet
**testall.py** — class: CustomLoader, TestRunner; function: find_exception_in_output, get_demo_tests, import_all, suite; 10 imports; method: CustomLoader.loadTestsFromModule, TestRunner.__call__, TestRunner.__init__; module: testall
**winxpgui.py** — 3 imports; module: winxpgui
**__init__.py** — function: SetupEnvironment, __PackageSupportBuildPath__; 7 imports; module: __init__
**CLSIDToClass.py** — function: GetClass, HasClass, RegisterCLSID, RegisterCLSIDsFromDict; 1 imports; module: CLSIDToClass
**__init__.py** — class: CDispatch, CoClassBaseClass, Constants, DispatchBaseClass, EventsProxy, VARIANT; function: CastTo, Dispatch, DispatchEx, DispatchWithEvents, GetActiveObject, GetObject; 8 imports; method: CDispatch.__dir__, CDispatch._wrap_dispatch_, CoClassBaseClass.__bool__, CoClassBaseClass.__call__, CoClassBaseClass.__getattr__, CoClassBaseClass.__init__; module: __init__
**build.py** — class: DispatchItem, LazyDispatchItem, MapEntry, NotSupportedException, OleItem, VTableItem; function: BuildCallList, MakeDefaultArgRepr, MakePublicAttributeName, _BuildArgList, _ResolveType, demunge_leading_underscores; 8 imports; method: DispatchItem.Build, DispatchItem.CountInOutOptArgs, DispatchItem.MakeDispatchFuncMethod, DispatchItem.MakeFuncMethod, DispatchItem.MakeVarArgsFuncMethod, DispatchItem._AddFunc_; module: build
**combrowse.py** — class: HLICLSID, HLICOM, HLICategory, HLICoClass, HLIHeadingCategory, HLIHeadingRegisterdTypeLibs; function: main; 9 imports; method: HLICLSID.CalculateIsExpandable, HLICLSID.GetSubList, HLICLSID.__init__, HLICOM.CalculateIsExpandable, HLICOM.GetText, HLICategory.GetSubList; module: combrowse
**connect.py** — class: SimpleConnection; 3 imports; method: SimpleConnection.Connect, SimpleConnection.Disconnect, SimpleConnection.__del__, SimpleConnection.__init__, SimpleConnection._wrap; module: connect
**dynamic.py** — class: CDispatch; function: Dispatch, DumbDispatch, MakeOleRepr, _GetDescInvokeType, _GetGoodDispatch, _GetGoodDispatchAndUserName; 10 imports; method: CDispatch._ApplyTypes_, CDispatch._FlagAsMethod, CDispatch._LazyAddAttr_, CDispatch._NewEnum, CDispatch._Release_, CDispatch._UpdateWithITypeInfo_; module: dynamic
**gencache.py** — function: AddModuleToCache, EnsureDispatch, EnsureModule, EnsureModuleForTypelibInterface, ForgetAboutTypelibInterface, GetClassForCLSID; 21 imports; module: gencache; rationale: [NOTE] OSError on file open must be caught by caller.
**genpy.py** — class: AliasItem, CoClassItem, DispatchItem, EnumerationItem, Generator, GeneratorProgress; function: MakeDefaultArgsForPropertyPut, MakeEventMethodName, MakeMapLineEntry, WriteAliasesForItem, WriteSinkEventMap; 7 imports; method: AliasItem.WriteAliasItem, AliasItem.__init__, CoClassItem.WriteClass, CoClassItem.__init__, DispatchItem.WriteCallbackClassBody, DispatchItem.WriteClass; module: genpy
**makepy.py** — class: GUIProgress, SimpleProgress; function: GenerateChildFromTypeLibSpec, GenerateFromTypeLibSpec, GetTypeLibsForSpec, ShowInfo, main, usage; 12 imports; method: GUIProgress.Close, GUIProgress.SetDescription, GUIProgress.Starting, GUIProgress.Tick, GUIProgress.__init__, SimpleProgress.Close; module: makepy
**selecttlb.py** — class: TypelibSpec; function: EnumKeys, EnumTlbs, FindTlbsWithDescription, SelectTlb; 4 imports; method: TypelibSpec.FromTypelib, TypelibSpec.Resolve, TypelibSpec.__eq__, TypelibSpec.__getitem__, TypelibSpec.__init__, TypelibSpec.__lt__; module: selecttlb
**tlbrowse.py** — class: TLBrowserException, TypeBrowseDialog; 7 imports; method: TypeBrowseDialog.CmdMemberListbox, TypeBrowseDialog.CmdTypeListbox, TypeBrowseDialog.GetTemplate, TypeBrowseDialog.OnAttachedObjectDeath, TypeBrowseDialog.OnFileOpen, TypeBrowseDialog.OnInitDialog; module: tlbrowse
**util.py** — class: EnumVARIANT, Enumerator, Iterator; function: WrapEnum; 2 imports; method: EnumVARIANT.__init__, EnumVARIANT._make_retval_, Enumerator.Clone, Enumerator.Next, Enumerator.Reset, Enumerator.__GetIndex; module: util
**connect.py** — class: ConnectableClient, ConnectableServer; function: CheckEvent, test; 7 imports; method: ConnectableClient.OnDoneIt, ConnectableClient.__init__, ConnectableClient._query_interface_, ConnectableServer.DoIt, ConnectableServer.NotifyDoneIt; module: connect
**dump_clipboard.py** — function: DumpClipboard; 2 imports; module: dump_clipboard
**eventsApartmentThreaded.py** — class: ExplorerEvents; function: TestExplorerEvents, WaitWhileProcessingMessages; 5 imports; method: ExplorerEvents.OnDocumentComplete, ExplorerEvents.OnQuit, ExplorerEvents.__init__; module: eventsApartmentThreaded; rationale: [NOTE] This example uses Internet Explorer, but it should not be considerd
**eventsFreeThreaded.py** — class: ExplorerEvents; function: TestExplorerEvents; 5 imports; method: ExplorerEvents.OnDocumentComplete, ExplorerEvents.OnQuit, ExplorerEvents.__init__; module: eventsFreeThreaded; rationale: [NOTE] This example uses Internet Explorer, but it should not be considered
**excelAddin.py** — class: ButtonEvent, ExcelAddin; function: RegisterAddin, UnregisterAddin; 10 imports; method: ButtonEvent.OnClick, ExcelAddin.OnAddInsUpdate, ExcelAddin.OnBeginShutdown, ExcelAddin.OnConnection, ExcelAddin.OnDisconnection, ExcelAddin.OnStartupComplete; module: excelAddin; rationale: [NOTE] If the AddIn fails with an error, Excel will re-register
**excelRTDServer.py** — class: ExcelRTDServer, RTDTopic, TimeServer, TimeTopic; 8 imports; method: ExcelRTDServer.ConnectData, ExcelRTDServer.CreateTopic, ExcelRTDServer.DisconnectData, ExcelRTDServer.Heartbeat, ExcelRTDServer.OnConnectData, ExcelRTDServer.OnDisconnectData; module: excelRTDServer
**iebutton.py** — class: IEButton, PyWin32InternetExplorerButton, Stub; function: DllRegisterServer, DllUnregisterServer, register, unregister; 7 imports; method: IEButton.Exec, IEButton.GetClassID, IEButton.QueryStatus, IEButton.SetSite, IEButton.__init__, Stub.__call__; module: iebutton
**ietoolbar.py** — class: IEToolbar, IEToolbarCtrl, Stub, TBBUTTON, WIN32STRUCT; function: DllInstall, DllRegisterServer, DllUnregisterServer; 17 imports; method: IEToolbar.CloseDW, IEToolbar.GetBandInfo, IEToolbar.GetClassID, IEToolbar.GetWindow, IEToolbar.Load, IEToolbar.Save; module: ietoolbar; rationale: [TODO] implement reg settings for standard toolbar button
**outlookAddin.py** — class: ButtonEvent, FolderEvent, OutlookAddin; function: RegisterAddin, UnregisterAddin; 9 imports; method: ButtonEvent.OnClick, FolderEvent.OnItemAdd, OutlookAddin.OnAddInsUpdate, OutlookAddin.OnBeginShutdown, OutlookAddin.OnConnection, OutlookAddin.OnDisconnection; module: outlookAddin; rationale: [NOTE] If the AddIn fails with an error, Outlook will re-register
**trybag.py** — class: Bag, Log, Target; function: test; 3 imports; method: Bag.Read, Bag.Write, Bag.__init__, Log.AddError, Target.GetClassID, Target.InitNew; module: trybag
**__init__.py** — module: __init__
**makegw.py** — function: _write_gw_cpp, _write_gw_h, _write_ifc_cpp, _write_ifc_h, make_framework_support, parse_arguments; 5 imports; module: makegw
**makegwenum.py** — function: _write_enumgw_cpp, _write_enumifc_cpp, is_interface_enum; module: makegwenum
**makegwparse.py** — class: ArgFormatter, ArgFormatterBSTR, ArgFormatterFloat, ArgFormatterGeneric, ArgFormatterHANDLE, ArgFormatterIDLIST; function: find_interface, make_arg_converter, parse_interface_info, test, test_regex; 3 imports; method: ArgFormatter.DeclareParseArgTupleInputConverter, ArgFormatter.GetAutoduckString, ArgFormatter.GetBuildForGatewayPostCode, ArgFormatter.GetBuildForGatewayPreCode, ArgFormatter.GetBuildForInterfacePostCode, ArgFormatter.GetBuildForInterfacePreCode; module: makegwparse; rationale: [NOTE] this is an [in] ... so use only builtin
**olectl.py** — function: MAKE_SCODE, STD_CTL_SCODE; 1 imports; module: olectl
**__init__.py** — module: __init__
**connect.py** — class: ConnectableServer; 5 imports; method: ConnectableServer.Advise, ConnectableServer.EnumConnectionPoints, ConnectableServer.EnumConnections, ConnectableServer.FindConnectionPoint, ConnectableServer.GetConnectionInterface, ConnectableServer.GetConnectionPointContainer; module: connect
**dispatcher.py** — class: DispatcherBase, DispatcherOutputDebugString, DispatcherTrace, DispatcherWin32trace; 10 imports; method: DispatcherBase._CreateInstance_, DispatcherBase._DeleteMemberByDispID_, DispatcherBase._DeleteMemberByName_, DispatcherBase._GetDispID_, DispatcherBase._GetIDsOfNames_, DispatcherBase._GetMemberName_; module: dispatcher
**exception.py** — class: COMException; function: IsCOMException, IsCOMServerException; 2 imports; method: COMException.__init__, COMException.__repr__; module: exception
**factory.py** — function: RegisterClassFactories, RevokeClassFactories; 1 imports; module: factory
**localserver.py** — function: main, serve; 4 imports; module: localserver; rationale: [NOTE] When NOT running in any sort of debugging mode,
**policy.py** — class: BasicWrapPolicy, DesignatedWrapPolicy, DynamicPolicy, EventHandlerPolicy, MappedWrapPolicy; function: CreateInstance, _import_module, call_func, resolve_func; 20 imports; method: BasicWrapPolicy._CreateInstance_, BasicWrapPolicy._DeleteMemberByDispID_, BasicWrapPolicy._DeleteMemberByName_, BasicWrapPolicy._GetDispID_, BasicWrapPolicy._GetIDsOfNames_, BasicWrapPolicy._GetMemberName_; module: policy; rationale: [NOTE] funcs have precedence over attrs (install attrs first), [NOTE] kwargs is being ignored..., [NOTE] lcid is being ignored..., [NOTE] lcid is being ignored..., [NOTE] lcid is being ignored..., [NOTE] serviceProvider is being ignored...
**register.py** — function: GetRegisteredServerOption, GetUnregisterServerKeys, ReExecuteElevated, RegisterClasses, RegisterPyComCategory, RegisterServer; 14 imports; module: register; rationale: [NOTE] ATL simply blows away the above three keys without the
**util.py** — class: Collection, FileStream, ListEnumerator, ListEnumeratorGateway; function: NewCollection, NewEnum, unwrap, wrap; 5 imports; method: Collection.Add, Collection.Count, Collection.Insert, Collection.Item, Collection.Remove, Collection._NewEnum; module: util
**PythonTools.py** — class: Tools; 5 imports; method: Tools.adddir, Tools.echo, Tools.reload, Tools.sleep; module: PythonTools
**dictionary.py** — class: DictionaryPolicy; function: Register; 10 imports; method: DictionaryPolicy._CreateInstance_, DictionaryPolicy._getidsofnames_, DictionaryPolicy._invokeex_, DictionaryPolicy._wrap_; module: dictionary
**interp.py** — class: Interpreter; function: Register; 3 imports; method: Interpreter.Eval, Interpreter.Exec, Interpreter.__init__; module: interp
**perfmon.py** — class: PerfMonQuery; 5 imports; method: PerfMonQuery.Query; module: perfmon
**test_pycomtest.py** — class: PyCOMTest, PyCOMTestMI; 7 imports; method: PyCOMTest.CheckVariantSafeArray, PyCOMTest.DoubleInOutString, PyCOMTest.DoubleString, PyCOMTest.Fire, PyCOMTest.GetLastVarArgs, PyCOMTest.GetMultipleInterfaces; module: test_pycomtest
**storagecon.py** — module: storagecon
**GenTestScripts.py** — function: CleanAll, GenerateAll, GenerateFromRegistered, GetGenPath; 8 imports; module: GenTestScripts
**__init__.py** — module: __init__
**daodump.py** — function: DumpAllContainers, DumpContainerDocuments, DumpDB, DumpFields, DumpRelations, DumpTables; 4 imports; module: daodump
**errorSemantics.py** — class: TestServer; function: test; 9 imports; method: TestServer.Clone, TestServer.Commit; module: errorSemantics
**pippo_server.py** — class: CPippo; function: BuildTypelib, UnregisterTypelib, main; 8 imports; method: CPippo.Method1, CPippo.Method2, CPippo.Method3, CPippo.__init__; module: pippo_server
**policySemantics.py** — class: PythonSemanticClass, Tester; function: DispExTest, SemanticTest; 7 imports; method: PythonSemanticClass.Add, PythonSemanticClass.In, PythonSemanticClass.Remove, PythonSemanticClass._Evaluate, PythonSemanticClass._NewEnum, PythonSemanticClass.__init__; module: policySemantics
**testADOEvents.py** — class: ADOEvents; function: Test, TestConnection; 6 imports; method: ADOEvents.OnBeginTransComplete, ADOEvents.OnCommitTransComplete, ADOEvents.OnConnectComplete, ADOEvents.OnDisconnect, ADOEvents.OnExecuteComplete, ADOEvents.OnInfoMessage; module: testADOEvents
**testAXScript.py** — class: AXScript; 6 imports; method: AXScript.setUp, AXScript.testCScript, AXScript.testHost; module: testAXScript
**testAccess.py** — function: CreateTestAccessDatabase, DoDumpAccessInfo, DumpAccessInfo, GenerateSupport, test; 9 imports; module: testAccess
**testArrays.py** — class: ArrayTest; function: _normalize_array; 5 imports; method: ArrayTest._doTest, ArrayTest.setUp, ArrayTest.tearDown, ArrayTest.testFourD, ArrayTest.testLargeD, ArrayTest.testOneD; module: testArrays
**testClipboard.py** — class: ClipboardTester, TestDataObject; function: WrapCOMObject; 9 imports; method: ClipboardTester.setUp, ClipboardTester.tearDown, ClipboardTester.testComToWin32, ClipboardTester.testDataObjectFlush, ClipboardTester.testDataObjectReset, ClipboardTester.testIsCurrentClipboard; module: testClipboard
**testCollections.py** — class: TestCase; function: MakeEmptyEnum, MakeTestEnum, TestEnum, TestEnumAgainst; 7 imports; method: TestCase.testEnum; module: testCollections
**testConversionErrors.py** — class: BadConversions, TestCase, TestException, Tester; function: test_ob; 4 imports; method: BadConversions.__float__, TestCase.test_float, Tester.TestValue; module: testConversionErrors
**testDCOM.py** — function: test; 4 imports; module: testDCOM; rationale: [NOTE] If you configured the object locally using dcomcnfg, you could
**testDates.py** — class: TestCase, Tester; function: test_ob; 7 imports; method: TestCase.check, TestCase.testLocal, TestCase.testMSTruncated, TestCase.testUTC, Tester.TestDate; module: testDates
**testDictionary.py** — class: TestCase; function: MakeTestDictionary, Register, TestDict, TestDictAgainst; 10 imports; method: TestCase.testDict; module: testDictionary
**testDynamic.py** — class: VeryPermissive; function: Test; 7 imports; method: VeryPermissive._dynamic_, VeryPermissive.write; module: testDynamic
**testExchange.py** — function: DumpFolder, DumpFolders, GetDefaultProfileName, TestAddress, TestUser, test; 6 imports; module: testExchange
**testExplorer.py** — class: ExplorerEvents; function: TestAll, TestExplorer, TestExplorerEvents, TestObjectFromWindow; 11 imports; method: ExplorerEvents.OnVisible; module: testExplorer
**testGIT.py** — function: BeginThreadsSimpleMarshal, CreateGIT, DoTestInterpInThread, TestInterp, TestInterpInThread, test; 7 imports; module: testGIT
**testGatewayAddresses.py** — class: DelegatedDummy, Dummy, Dummy2, Dummy3; function: CheckObjectIdentity, CheckSameCOMObject, FailObjectIdentity, TestGatewayInheritance, TestMultiInterface, test; 3 imports; method: Dummy3._query_interface_; module: testGatewayAddresses
**testIterators.py** — class: SomeObject, VBTestCase, WrappedPythonCOMServerTestCase, _BaseTestCase; function: suite; 7 imports; method: SomeObject.GetCollection, SomeObject.__init__, VBTestCase.setUp, VBTestCase.tearDown, WrappedPythonCOMServerTestCase.setUp, WrappedPythonCOMServerTestCase.tearDown; module: testIterators
**testMSOffice.py** — function: TestAll, TestWord, TestWord7, TestWord8, TestWord8OldStyle, TextExcel; 9 imports; module: testMSOffice; rationale: [NOTE] Iterating on paras doesn't seem to work - no error, just doesn't work
**testMSOfficeEvents.py** — function: TestExcel, TestWord, _CheckSeenEvents, _WaitForFinish, test; 7 imports; module: testMSOfficeEvents
**testMarshal.py** — class: ThreadInterpCase; 7 imports; method: ThreadInterpCase.BeginThreadsFastMarshal, ThreadInterpCase.BeginThreadsSimpleMarshal, ThreadInterpCase._DoTestMarshal, ThreadInterpCase._doTestInThread, ThreadInterpCase._testInterpInThread, ThreadInterpCase.testSimpleMarshal; module: testMarshal
**testPersist.py** — class: LockBytes, OleClientSite; function: test; 13 imports; method: LockBytes.Flush, LockBytes.LockRegion, LockBytes.ReadAt, LockBytes.SetSize, LockBytes.Stat, LockBytes.UnlockRegion; module: testPersist
**testPippo.py** — class: PippoTester; 8 imports; method: PippoTester._testArray, PippoTester.setUp, PippoTester.testByteArrays, PippoTester.testLeaks, PippoTester.testLeaksGencache, PippoTester.testNumpyArrays; module: testPippo
**testPyComTest.py** — class: ArrayOfStructsTestStruct, NotInTypeLibraryTestStruct, RandomEventHandler, TestStruct1, TestStruct2, TestStruct3; function: GetMemoryUsage, TestApplyResult, TestArrayOfStructs, TestCommon, TestConstant, TestCounter; 27 imports; method: RandomEventHandler.OnFire, RandomEventHandler.OnFireWithNamedParams, RandomEventHandler._DumpFireds, RandomEventHandler._Init, Tester.testDynamic, Tester.testGenerated; module: testPyComTest
**testPyScriptlet.js** — function: check, print; module: testPyScriptlet
**testROT.py** — class: TestROT; 4 imports; method: TestROT.testit; module: testROT
**testServers.py** — class: ConnectionsTestCase, InterpCase; function: TestConnections; 7 imports; method: ConnectionsTestCase.testConnections, InterpCase._testInterp, InterpCase.setUp, InterpCase.testAny, InterpCase.testInproc, InterpCase.testLocalServer; module: testServers
**testShell.py** — class: FILEGROUPDESCRIPTORTester, FileOperationTester, PIDLTester, ShellTester; 13 imports; method: FILEGROUPDESCRIPTORTester._getTestTimes, FILEGROUPDESCRIPTORTester._testRT, FILEGROUPDESCRIPTORTester._testSimple, FILEGROUPDESCRIPTORTester.testComplex, FILEGROUPDESCRIPTORTester.testSimpleBytes, FILEGROUPDESCRIPTORTester.testSimpleUnicode; module: testShell
**testStorage.py** — class: TestEnum; 5 imports; method: TestEnum.testit; module: testStorage
**testStreams.py** — class: BadStream, Persists, Stream, StreamTest; 4 imports; method: BadStream.Read, Persists.GetClassID, Persists.GetSizeMax, Persists.InitNew, Persists.IsDirty, Persists.Load; module: testStreams
**testWMI.py** — class: Simple; 3 imports; method: Simple.testit; module: testWMI
**testall.py** — class: PippoTest, PyCOMTest; function: CleanGenerated, ExecuteSilentlyIfOK, RemoveRefCountOutput, get_test_mod_and_func, make_test_suite, usage; 24 imports; method: PippoTest.testit, PyCOMTest.testit; module: testall
**testmakepy.py** — function: TestAll, TestBuildAll, TestBuildConcurrent, _TestEnsureModule; 11 imports; module: testmakepy
**testvb.py** — class: TestObject; function: DoTestAll, TestAll, TestArrays, TestCollections, TestObjectSemantics, TestStructs; 11 imports; method: TestObject.CallbackArrayResult, TestObject.CallbackArrayResultOneArrayByRef, TestObject.CallbackArrayResultWrongSize, TestObject.CallbackResultOneByRef, TestObject.CallbackResultOneByRefButReturnNone, TestObject.CallbackString; module: testvb
**testvbscript_regexp.py** — class: RegexTest; 4 imports; method: RegexTest._CheckMatches, RegexTest._TestVBScriptRegex, RegexTest.testDynamic, RegexTest.testGenerated; module: testvbscript_regexp
**testxslt.js** — module: testxslt
**testxslt.py** — class: XSLT; 4 imports; method: XSLT.testAll; module: testxslt
**util.py** — class: CaptureWriter, LogHandler, ShellTestCase, _CapturingFunctionTestCase; function: CapturingFunctionTestCase, CheckClean, ExecuteShellCommand, RegisterPythonServer, assertRaisesCOM_HRESULT, restore_test_logger; 15 imports; method: CaptureWriter.__init__, CaptureWriter.capture, CaptureWriter.clear, CaptureWriter.get_captured, CaptureWriter.get_num_lines_captured, CaptureWriter.release; module: util
**universal.py** — class: Arg, Definition, Method; function: RegisterInterfaces, _CalcTypeSize, _doCreateVTable; 3 imports; method: Arg.__init__, Definition.__init__, Definition.dispatch, Definition.iid, Definition.vtbl_argcounts, Definition.vtbl_argsizes; module: universal
**util.py** — function: IIDToInterfaceName; 3 imports; module: util
**__init__.py** — class: ADSIDispatch, ADSIEnumerator; function: ADsGetObject, ADsOpenObject, _get_good_ret; 7 imports; method: ADSIDispatch.QueryInterface, ADSIDispatch._NewEnum, ADSIDispatch.__getattr__, ADSIDispatch._wrap_dispatch_, ADSIEnumerator.__GetIndex, ADSIEnumerator.__call__; module: __init__
**adsicon.py** — function: _HRESULT_TYPEDEF_; module: adsicon
**objectPicker.py** — function: main; 4 imports; module: objectPicker
**scp.py** — class: HelpFormatter, _NoDefault; function: AllowAccessToScpProperties, ScpCreate, ScpDelete, SpnRegister, UserChangePassword, _get_option; 12 imports; method: HelpFormatter.format_description; module: scp
**search.py** — function: _guid_from_buffer, _sid_from_buffer, getADsTypeName, getGC, log, main; 6 imports; module: search
**test.py** — function: DumpAllObjects, DumpGC, DumpLocalGroups, DumpLocalUsers, DumpRoot, DumpSchema; 9 imports; module: test
**__init__.py** — 1 imports; module: __init__
**EditSecurity.py** — class: SecurityInformation; 26 imports; method: SecurityInformation.EditSecurity, SecurityInformation.GetAccessRights, SecurityInformation.GetInheritTypes, SecurityInformation.GetObjectInformation, SecurityInformation.GetSecurity, SecurityInformation.MapGeneric; module: EditSecurity
**EditServiceSecurity.py** — class: ServiceSecurity; 17 imports; method: ServiceSecurity.EditSecurity, ServiceSecurity.GetAccessRights, ServiceSecurity.GetInheritTypes, ServiceSecurity.GetObjectInformation, ServiceSecurity.GetSecurity, ServiceSecurity.MapGeneric; module: EditServiceSecurity
**__init__.py** — 1 imports; module: __init__
**__init__.py** — 1 imports; module: __init__
**adb.py** — class: Adb, OutputReflector; function: Debugger, OnSetBreakPoint, _dumpf, fnull; 14 imports; method: Adb.AttachApp, Adb.CloseApp, Adb.OnBreakFlagChange, Adb.OnClose, Adb.OnConnectDebugger, Adb.OnCreateThread; module: adb
**codecontainer.py** — class: SourceCodeContainer, SourceModuleContainer; 13 imports; method: SourceCodeContainer.GetCodeContextAtPosition, SourceCodeContainer.GetFileName, SourceCodeContainer.GetLine, SourceCodeContainer.GetLineOfPosition, SourceCodeContainer.GetName, SourceCodeContainer.GetNextLine; module: codecontainer
**contexts.py** — class: DebugCodeContext, EnumDebugCodeContexts; 4 imports; method: DebugCodeContext.EnumCodeContexts, DebugCodeContext.GetDocument, DebugCodeContext.GetDocumentContext, DebugCodeContext.SetBreakPoint, DebugCodeContext._Close, DebugCodeContext.__init__; module: contexts; rationale: [NOTE] We also implement the IDebugDocumentContext interface for Simple Hosts.
**debugger.py** — class: AXDebugger, CodeContainerProvider, ModuleTreeNode, OriginalInterfaceMaker, SimpleHostStyleInterfaceMaker; function: Break, BuildModule, RefreshAllModules, _GetCurrentDebugger, dosomething, dosomethingelse; 9 imports; method: AXDebugger.Break, AXDebugger.Close, AXDebugger.CreateApplicationNode, AXDebugger.RefreshAllModules, AXDebugger.__init__, CodeContainerProvider.Close; module: debugger
**documents.py** — class: CodeContainerProvider, DebugDocumentProvider, DebugDocumentText; function: GetGoodFileName; 7 imports; method: CodeContainerProvider.AddCodeContainer, CodeContainerProvider.Close, CodeContainerProvider.FromFileName, CodeContainerProvider.__init__, DebugDocumentProvider.GetDocument, DebugDocumentProvider.GetDocumentClassId; module: documents
**dump.py** — function: DumpDebugApplicationNode, dumpall; 4 imports; module: dump
**expressions.py** — class: DebugProperty, EnumDebugPropertyInfo, Expression, ExpressionContext, ProvideExpressionContexts; function: GetPropertyInfo, MakeEnumDebugProperty, MakeNiceString; 10 imports; method: DebugProperty.EnumMembers, DebugProperty.GetExtendedInfo, DebugProperty.GetParent, DebugProperty.GetPropertyInfo, DebugProperty.SetValueAsString, DebugProperty.__init__; module: expressions
**gateways.py** — class: DebugApplicationNode, DebugApplicationNodeEvents, DebugCodeContext, DebugDocument, DebugDocumentContext, DebugDocumentHost; 8 imports; method: DebugApplicationNode.Attach, DebugApplicationNode.Close, DebugApplicationNode.Detach, DebugApplicationNode.EnumChildren, DebugApplicationNode.GetParent, DebugApplicationNode.SetDocumentProvider; module: gateways
**stackframe.py** — class: DebugStackFrame, DebugStackFrameSniffer, EnumDebugStackFrames, StackFrameDebugProperty; 7 imports; method: DebugStackFrame.GetCodeContext, DebugStackFrame.GetDebugProperty, DebugStackFrame.GetDescriptionString, DebugStackFrame.GetLanguageString, DebugStackFrame.GetThread, DebugStackFrame.__init__; module: stackframe
**util.py** — class: Dispatcher; function: RaiseNotImpl, _wrap, trace; 10 imports; method: Dispatcher._Invoke_, Dispatcher._QueryInterface_, Dispatcher.__init__; module: util
**__init__.py** — 1 imports; module: __init__
**asputil.py** — function: iif; module: asputil
**__init__.py** — module: __init__
**debug.py** — class: ActiveScriptDebug, DebugCodeBlockContainer, DebugManager, EnumDebugCodeContexts; function: trace; 12 imports; method: ActiveScriptDebug.EnumCodeContextsOfPosition, ActiveScriptDebug.GetScriptTextAttributes, ActiveScriptDebug.GetScriptletTextAttributes, ActiveScriptDebug._Close, ActiveScriptDebug.__init__, ActiveScriptDebug._query_interface_; module: debug
**error.py** — class: AXScriptException, IActiveScriptError; function: AddCR, ExpandTabs, FormatForAX, ProcessAXScriptException; 16 imports; method: AXScriptException.ExtractTracebackInfo, AXScriptException._BuildFromOther, AXScriptException._BuildFromSyntaxError, AXScriptException.__BuildFromException, AXScriptException.__init__, IActiveScriptError.GetExceptionInfo; module: error; rationale: [NOTE] 'line' will now be unicode.
**framework.py** — class: AXScriptCodeBlock, COMScript, Event, EventSink, SafeOutput, ScriptItem; function: MakeValidSysOuts, RaiseAssert, RemoveCR, dumptypeinfo, profile, trace; 20 imports; method: AXScriptCodeBlock.GetDisplayName, AXScriptCodeBlock.GetFileName, AXScriptCodeBlock.GetLineNo, AXScriptCodeBlock.__init__, COMScript.AddNamedItem, COMScript.AddScriptlet; module: framework
**pydumper.py** — class: AXScriptAttribute, NamedScriptAttribute, PyScript; function: Register; 7 imports; module: pydumper
**pyscript.py** — class: AXScriptAttribute, AXScriptCodeBlock, NamedScriptAttribute, PyScript, ScriptItem; function: AddCR, DllRegisterServer, ExpandTabs, Register, debug_attr_print; 15 imports; method: AXScriptAttribute._Close_, AXScriptAttribute._DoFindAttribute_, AXScriptAttribute._FindAttribute_, AXScriptAttribute.__getattr__, AXScriptAttribute.__init__, AXScriptCodeBlock.GetDisplayName; module: pyscript
**pyscript_rexec.py** — class: PyScriptRExec; 3 imports; method: PyScriptRExec._GetSupportedInterfaceSafetyOptions; module: pyscript_rexec
**scriptdispatch.py** — class: ScriptDispatch, StrictDynamicPolicy; function: MakeScriptDispatch, _wrap; 8 imports; method: ScriptDispatch.__init__, ScriptDispatch._dynamic_, StrictDynamicPolicy._getdispid_, StrictDynamicPolicy._getmembername_, StrictDynamicPolicy._wrap_; module: scriptdispatch
**axsite.py** — class: AXEngine, AXSite; 5 imports; method: AXEngine.AddCode, AXEngine.AddNamedItem, AXEngine.Close, AXEngine.EvalCode, AXEngine.GetScriptDispatch, AXEngine.SetScriptState; module: axsite
**leakTest.py** — class: MyCollection, MySite, Test, TestConnectServer; function: TestEngine, doTestEngine, dotestall, testall; 8 imports; method: MyCollection._NewEnum, MySite.OnScriptError, Test.__init__, Test.echo, TestConnectServer.Broadcast, TestConnectServer.NotifyDoneIt; module: leakTest
**testHost.py** — class: EngineTester, MyCollection, MySite, Test, TestConnectServer; function: _CheckEngineState; 11 imports; method: EngineTester._TestEngine, EngineTester.testPython, EngineTester.testPythonUnicodeError, EngineTester.testVB, EngineTester.testVBExceptions, MyCollection._NewEnum; module: testHost
**testHost4Dbg.py** — class: MySite, ObjectModel; function: TestEngine; 7 imports; method: MySite.OnScriptError, ObjectModel.echo, ObjectModel.msgbox; module: testHost4Dbg
**__init__.py** — 1 imports; module: __init__
**show_all_jobs.py** — 2 imports; module: show_all_jobs
**test_bits.py** — class: BackgroundJobCallback; 7 imports; method: BackgroundJobCallback.JobError, BackgroundJobCallback.JobModification, BackgroundJobCallback.JobTransferred, BackgroundJobCallback._print_error; module: test_bits
**__init__.py** — 1 imports; module: __init__
**__init__.py** — module: __init__
**ds_record.py** — function: wav_header_pack; 6 imports; module: ds_record
**ds_test.py** — class: DSBCAPSTest, DSBUFFERDESCTest, DSCAPSTest, DSCBCAPSTest, DSCBUFFERDESCTest, DSCCAPSTest; function: wav_header_pack, wav_header_unpack; 10 imports; method: DSBCAPSTest.test_1_Type, DSBCAPSTest.test_2_Attr, DSBUFFERDESCTest.invalid_format, DSBUFFERDESCTest.test_1_Type, DSBUFFERDESCTest.test_2_Attr, DSBUFFERDESCTest.test_3_invalid_format; module: ds_test
**__init__.py** — module: __init__
**filterDemo.py** — class: FileParser; function: _usage; 8 imports; method: FileParser.Close, FileParser.Parse, FileParser.__init__, FileParser._bind_to_filter, FileParser._get_properties, FileParser._get_text; module: filterDemo
**ifiltercon.py** — 1 imports; module: ifiltercon
**__init__.py** — 1 imports; module: __init__
**inetcon.py** — module: inetcon
**__init__.py** — 4 imports; module: __init__
**mapisend.py** — function: SendEMAPIMail; 2 imports; module: mapisend; rationale: [NOTE] you can use the resolveaddress functions for this. but you may get headaches
**emsabtags.py** — 41 imports; module: emsabtags
**mapitags.py** — function: PROP_ID, PROP_TAG, PROP_TYPE; module: mapitags
**mapiutil.py** — function: GetAllProperties, GetMapiTypeName, GetPropTagName, GetProperties, GetScodeString, SetProperties; 5 imports; module: mapiutil
**__init__.py** — module: __init__
**pscon.py** — 1 imports; module: pscon
**testpropsys.py** — 2 imports; module: testpropsys
**__init__.py** — 1 imports; module: __init__
**IActiveDesktop.py** — 4 imports; module: IActiveDesktop
**IFileOperationProgressSink.py** — class: FileOperationProgressSink; function: CreateSink, decode_flags; 4 imports; method: FileOperationProgressSink.FinishOperations, FileOperationProgressSink.PauseTimer, FileOperationProgressSink.PostCopyItem, FileOperationProgressSink.PostDeleteItem, FileOperationProgressSink.PostMoveItem, FileOperationProgressSink.PostNewItem; module: IFileOperationProgressSink
**IShellLinkDataList.py** — 6 imports; module: IShellLinkDataList
**ITransferAdviseSink.py** — class: TransferAdviseSink; function: CreateSink, decode_flags; 4 imports; method: TransferAdviseSink.ConfirmEncryptionLoss, TransferAdviseSink.ConfirmOverwrite, TransferAdviseSink.FileFailure, TransferAdviseSink.PropertyFailure, TransferAdviseSink.SubStreamFailure, TransferAdviseSink.UpdateProgress; module: ITransferAdviseSink
**IUniformResourceLocator.py** — class: InternetShortcut; 5 imports; method: InternetShortcut.__getattr__, InternetShortcut.__init__, InternetShortcut.load, InternetShortcut.save; module: IUniformResourceLocator
**browse_for_folder.py** — function: BrowseCallbackProc; 4 imports; module: browse_for_folder
**create_link.py** — class: PyShortcut; 5 imports; method: PyShortcut.__getattr__, PyShortcut.__init__, PyShortcut.load, PyShortcut.save; module: create_link
**dump_link.py** — function: DumpFavorites, DumpLink, FavDumper; 7 imports; module: dump_link
**explorer_browser.py** — class: EventHandler, MainWindow; function: main; 9 imports; method: EventHandler.OnNavigationComplete, EventHandler.OnNavigationFailed, EventHandler.OnNavigationPending, EventHandler.OnViewCreated, MainWindow.OnCommand, MainWindow.OnDestroy; module: explorer_browser
**column_provider.py** — class: ColumnProvider; function: DllRegisterServer, DllUnregisterServer; 10 imports; method: ColumnProvider.GetClassID, ColumnProvider.GetColumnInfo, ColumnProvider.GetItemData, ColumnProvider.Initialize; module: column_provider
**context_menu.py** — class: ShellExtension; function: DllRegisterServer, DllUnregisterServer; 8 imports; method: ShellExtension.GetCommandString, ShellExtension.Initialize, ShellExtension.InvokeCommand, ShellExtension.QueryContextMenu; module: context_menu
**copy_hook.py** — class: ShellExtension; function: DllRegisterServer, DllUnregisterServer; 7 imports; method: ShellExtension.CopyCallBack; module: copy_hook
**empty_volume_cache.py** — class: EmptyVolumeCache; function: DllRegisterServer, DllUnregisterServer; 12 imports; method: EmptyVolumeCache.Deactivate, EmptyVolumeCache.GetSpaceUsed, EmptyVolumeCache.Initialize, EmptyVolumeCache.InitializeEx, EmptyVolumeCache.Purge, EmptyVolumeCache.ShowProperties; module: empty_volume_cache
**folder_view.py** — class: Command, ContextMenu, ExplorerCommand, ExplorerCommandProvider, FolderViewCategorizer, FolderViewCategorizer_Level; function: DisplayItem, DllRegisterServer, DllUnregisterServer, LoadString, NewEnum, _make_ids; 20 imports; method: Command.__init__, Command.tuple, ContextMenu.GetCommandString, ContextMenu.GetSite, ContextMenu.Initialize, ContextMenu.InvokeCommand; module: folder_view; rationale: [NOTE] this isn't always appropriate!  See overrides below
**icon_handler.py** — class: ShellExtension; function: DllRegisterServer, DllUnregisterServer; 10 imports; method: ShellExtension.Extract, ShellExtension.GetIconLocation, ShellExtension.Load; module: icon_handler
**shell_view.py** — class: FileSystemView, ScintillaShellView, ShellFolderBase, ShellFolderDirectory, ShellFolderFile, ShellFolderFileSystem; function: DllRegisterServer, DllUnregisterServer, GetFolderAndPIDLForPath, get_clbr_for_file; 22 imports; method: FileSystemView.ContextSensitiveHelp, FileSystemView.CreateViewWindow, FileSystemView.DestroyViewWindow, FileSystemView.GetCurrentInfo, FileSystemView.GetItemObject, FileSystemView.GetWindow; module: shell_view; rationale: [NOTE] This function it *not* called each time the selection changes.
**shellexecuteex.py** — function: ExplorePIDL; 3 imports; module: shellexecuteex
**viewstate.py** — function: update_colinfo; 5 imports; module: viewstate
**walk_shell_folders.py** — function: walk; 2 imports; module: walk_shell_folders
**shellcon.py** — function: EIRESID; module: shellcon
**testSHFileOperation.py** — function: testSHFileOperation, testSHNAMEMAPPINGS; 4 imports; module: testSHFileOperation
**testShellFolder.py** — 2 imports; module: testShellFolder
**testShellItem.py** — class: TestShellItem; 4 imports; method: TestShellItem.assertShellItemsEqual, TestShellItem.test_create_in_known_folder, TestShellItem.test_create_item_with_parent, TestShellItem.test_idlist_roundtrip, TestShellItem.test_parsing_name, TestShellItem.test_parsing_relative; module: testShellItem
**__init__.py** — 1 imports; module: __init__
**test_addtask.py** — 6 imports; module: test_addtask
**test_addtask_1.py** — 4 imports; module: test_addtask_1
**test_addtask_2.py** — 3 imports; module: test_addtask_2
**test_localsystem.py** — module: test_localsystem
**pywin32_postinstall.py** — class: Tee; function: CopyTo, LoadSystemModule, RegisterCOMObjects, RegisterHelpFile, RegisterPythonwin, SetPyKeyVal; 19 imports; method: Tee.__init__, Tee.flush, Tee.write; module: pywin32_postinstall; rationale: [NOTE] This used to be run from inside the bdist_wininst created binary un/installer.
**pywin32_testall.py** — function: find_and_run, main, run_test; 5 imports; module: pywin32_testall

---
*Generated by graphify-plus v0.2.0*