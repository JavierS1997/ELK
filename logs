sudo bin/logstash -f /Users/Javier/ELK/Data/logstash-cars.conf --log.level debug
Password:
Sending Logstash logs to /Users/Javier/ELK/logstash-7.9.2/logs which is now configured via log4j2.properties
[2020-10-05T17:12:53,506][INFO ][logstash.runner          ] Starting Logstash {"logstash.version"=>"7.9.2", "jruby.version"=>"jruby 9.2.13.0 (2.5.7) 2020-08-03 9a89c94bcc Java HotSpot(TM) 64-Bit Server VM 25.121-b13 on 1.8.0_121-b13 +indy +jit [darwin-x86_64]"}
[2020-10-05T17:12:54,062][DEBUG][logstash.modules.scaffold] Found module {:module_name=>"netflow", :directory=>"/Users/Javier/ELK/logstash-7.9.2/modules/netflow/configuration"}
[2020-10-05T17:12:54,073][DEBUG][logstash.plugins.registry] Adding plugin to the registry {:name=>"netflow", :type=>:modules, :class=>#<LogStash::Modules::Scaffold:0x37630101 @directory="/Users/Javier/ELK/logstash-7.9.2/modules/netflow/configuration", @module_name="netflow", @kibana_version_parts=["6", "0", "0"]>}
[2020-10-05T17:12:54,081][DEBUG][logstash.modules.scaffold] Found module {:module_name=>"fb_apache", :directory=>"/Users/Javier/ELK/logstash-7.9.2/modules/fb_apache/configuration"}
[2020-10-05T17:12:54,091][DEBUG][logstash.plugins.registry] Adding plugin to the registry {:name=>"fb_apache", :type=>:modules, :class=>#<LogStash::Modules::Scaffold:0x1a420390 @directory="/Users/Javier/ELK/logstash-7.9.2/modules/fb_apache/configuration", @module_name="fb_apache", @kibana_version_parts=["6", "0", "0"]>}
[2020-10-05T17:12:54,423][DEBUG][logstash.runner          ] -------- Logstash Settings (* means modified) ---------
[2020-10-05T17:12:54,446][DEBUG][logstash.runner          ] node.name: "Javiers-Air-2.home"
[2020-10-05T17:12:54,469][DEBUG][logstash.runner          ] *path.config: "/Users/Javier/ELK/Data/logstash-cars.conf"
[2020-10-05T17:12:54,474][DEBUG][logstash.runner          ] path.data: "/Users/Javier/ELK/logstash-7.9.2/data"
[2020-10-05T17:12:54,478][DEBUG][logstash.runner          ] modules.cli: []
[2020-10-05T17:12:54,486][DEBUG][logstash.runner          ] modules: []
[2020-10-05T17:12:54,491][DEBUG][logstash.runner          ] modules_list: []
[2020-10-05T17:12:54,504][DEBUG][logstash.runner          ] modules_variable_list: []
[2020-10-05T17:12:54,508][DEBUG][logstash.runner          ] modules_setup: false
[2020-10-05T17:12:54,511][DEBUG][logstash.runner          ] config.test_and_exit: false
[2020-10-05T17:12:54,514][DEBUG][logstash.runner          ] config.reload.automatic: false
[2020-10-05T17:12:54,517][DEBUG][logstash.runner          ] config.reload.interval: #<LogStash::Util::TimeValue:0x2cb34e1e @duration=3, @time_unit=:second>
[2020-10-05T17:12:54,521][DEBUG][logstash.runner          ] config.support_escapes: false
[2020-10-05T17:12:54,523][DEBUG][logstash.runner          ] config.field_reference.parser: "STRICT"
[2020-10-05T17:12:54,534][DEBUG][logstash.runner          ] metric.collect: true
[2020-10-05T17:12:54,539][DEBUG][logstash.runner          ] pipeline.id: "main"
[2020-10-05T17:12:54,546][DEBUG][logstash.runner          ] pipeline.system: false
[2020-10-05T17:12:54,554][DEBUG][logstash.runner          ] pipeline.workers: 4
[2020-10-05T17:12:54,562][DEBUG][logstash.runner          ] pipeline.batch.size: 125
[2020-10-05T17:12:54,571][DEBUG][logstash.runner          ] pipeline.batch.delay: 50
[2020-10-05T17:12:54,575][DEBUG][logstash.runner          ] pipeline.unsafe_shutdown: false
[2020-10-05T17:12:54,579][DEBUG][logstash.runner          ] pipeline.java_execution: true
[2020-10-05T17:12:54,583][DEBUG][logstash.runner          ] pipeline.reloadable: true
[2020-10-05T17:12:54,586][DEBUG][logstash.runner          ] pipeline.plugin_classloaders: false
[2020-10-05T17:12:54,591][DEBUG][logstash.runner          ] pipeline.separate_logs: false
[2020-10-05T17:12:54,594][DEBUG][logstash.runner          ] pipeline.ordered: "auto"
[2020-10-05T17:12:54,597][DEBUG][logstash.runner          ] path.plugins: []
[2020-10-05T17:12:54,601][DEBUG][logstash.runner          ] config.debug: false
[2020-10-05T17:12:54,604][DEBUG][logstash.runner          ] *log.level: "debug" (default: "info")
[2020-10-05T17:12:54,607][DEBUG][logstash.runner          ] version: false
[2020-10-05T17:12:54,610][DEBUG][logstash.runner          ] help: false
[2020-10-05T17:12:54,613][DEBUG][logstash.runner          ] log.format: "plain"
[2020-10-05T17:12:54,615][DEBUG][logstash.runner          ] http.enabled: true
[2020-10-05T17:12:54,618][DEBUG][logstash.runner          ] http.host: "127.0.0.1"
[2020-10-05T17:12:54,639][DEBUG][logstash.runner          ] http.port: 9600..9700
[2020-10-05T17:12:54,643][DEBUG][logstash.runner          ] http.environment: "production"
[2020-10-05T17:12:54,647][DEBUG][logstash.runner          ] queue.type: "memory"
[2020-10-05T17:12:54,651][DEBUG][logstash.runner          ] queue.drain: false
[2020-10-05T17:12:54,654][DEBUG][logstash.runner          ] queue.page_capacity: 67108864
[2020-10-05T17:12:54,661][DEBUG][logstash.runner          ] queue.max_bytes: 1073741824
[2020-10-05T17:12:54,672][DEBUG][logstash.runner          ] queue.max_events: 0
[2020-10-05T17:12:54,681][DEBUG][logstash.runner          ] queue.checkpoint.acks: 1024
[2020-10-05T17:12:54,687][DEBUG][logstash.runner          ] queue.checkpoint.writes: 1024
[2020-10-05T17:12:54,694][DEBUG][logstash.runner          ] queue.checkpoint.interval: 1000
[2020-10-05T17:12:54,698][DEBUG][logstash.runner          ] queue.checkpoint.retry: false
[2020-10-05T17:12:54,706][DEBUG][logstash.runner          ] dead_letter_queue.enable: false
[2020-10-05T17:12:54,709][DEBUG][logstash.runner          ] dead_letter_queue.max_bytes: 1073741824
[2020-10-05T17:12:54,717][DEBUG][logstash.runner          ] slowlog.threshold.warn: #<LogStash::Util::TimeValue:0x22272bac @duration=-1, @time_unit=:nanosecond>
[2020-10-05T17:12:54,724][DEBUG][logstash.runner          ] slowlog.threshold.info: #<LogStash::Util::TimeValue:0x14d25248 @duration=-1, @time_unit=:nanosecond>
[2020-10-05T17:12:54,728][DEBUG][logstash.runner          ] slowlog.threshold.debug: #<LogStash::Util::TimeValue:0xcff1a53 @duration=-1, @time_unit=:nanosecond>
[2020-10-05T17:12:54,734][DEBUG][logstash.runner          ] slowlog.threshold.trace: #<LogStash::Util::TimeValue:0x9af804b @duration=-1, @time_unit=:nanosecond>
[2020-10-05T17:12:54,741][DEBUG][logstash.runner          ] keystore.classname: "org.logstash.secret.store.backend.JavaKeyStore"
[2020-10-05T17:12:54,746][DEBUG][logstash.runner          ] keystore.file: "/Users/Javier/ELK/logstash-7.9.2/config/logstash.keystore"
[2020-10-05T17:12:54,750][DEBUG][logstash.runner          ] path.queue: "/Users/Javier/ELK/logstash-7.9.2/data/queue"
[2020-10-05T17:12:54,756][DEBUG][logstash.runner          ] path.dead_letter_queue: "/Users/Javier/ELK/logstash-7.9.2/data/dead_letter_queue"
[2020-10-05T17:12:54,772][DEBUG][logstash.runner          ] path.settings: "/Users/Javier/ELK/logstash-7.9.2/config"
[2020-10-05T17:12:54,778][DEBUG][logstash.runner          ] path.logs: "/Users/Javier/ELK/logstash-7.9.2/logs"
[2020-10-05T17:12:54,783][DEBUG][logstash.runner          ] xpack.management.enabled: false
[2020-10-05T17:12:54,787][DEBUG][logstash.runner          ] xpack.management.logstash.poll_interval: #<LogStash::Util::TimeValue:0x12cea099 @duration=5, @time_unit=:second>
[2020-10-05T17:12:54,789][DEBUG][logstash.runner          ] xpack.management.pipeline.id: ["main"]
[2020-10-05T17:12:54,792][DEBUG][logstash.runner          ] xpack.management.elasticsearch.username: "logstash_system"
[2020-10-05T17:12:54,796][DEBUG][logstash.runner          ] xpack.management.elasticsearch.hosts: ["https://localhost:9200"]
[2020-10-05T17:12:54,800][DEBUG][logstash.runner          ] xpack.management.elasticsearch.ssl.verification_mode: "certificate"
[2020-10-05T17:12:54,806][DEBUG][logstash.runner          ] xpack.management.elasticsearch.sniffing: false
[2020-10-05T17:12:54,822][DEBUG][logstash.runner          ] xpack.monitoring.enabled: false
[2020-10-05T17:12:54,826][DEBUG][logstash.runner          ] xpack.monitoring.elasticsearch.hosts: ["http://localhost:9200"]
[2020-10-05T17:12:54,830][DEBUG][logstash.runner          ] xpack.monitoring.collection.interval: #<LogStash::Util::TimeValue:0x72a48403 @duration=10, @time_unit=:second>
[2020-10-05T17:12:54,834][DEBUG][logstash.runner          ] xpack.monitoring.collection.timeout_interval: #<LogStash::Util::TimeValue:0x21fba6fd @duration=10, @time_unit=:minute>
[2020-10-05T17:12:54,838][DEBUG][logstash.runner          ] xpack.monitoring.elasticsearch.username: "logstash_system"
[2020-10-05T17:12:54,842][DEBUG][logstash.runner          ] xpack.monitoring.elasticsearch.ssl.verification_mode: "certificate"
[2020-10-05T17:12:54,847][DEBUG][logstash.runner          ] xpack.monitoring.elasticsearch.sniffing: false
[2020-10-05T17:12:54,850][DEBUG][logstash.runner          ] xpack.monitoring.collection.pipeline.details.enabled: true
[2020-10-05T17:12:54,853][DEBUG][logstash.runner          ] xpack.monitoring.collection.config.enabled: true
[2020-10-05T17:12:54,855][DEBUG][logstash.runner          ] monitoring.enabled: false
[2020-10-05T17:12:54,858][DEBUG][logstash.runner          ] monitoring.elasticsearch.hosts: ["http://localhost:9200"]
[2020-10-05T17:12:54,860][DEBUG][logstash.runner          ] monitoring.collection.interval: #<LogStash::Util::TimeValue:0x17d99e0f @duration=10, @time_unit=:second>
[2020-10-05T17:12:54,862][DEBUG][logstash.runner          ] monitoring.collection.timeout_interval: #<LogStash::Util::TimeValue:0x418b946b @duration=10, @time_unit=:minute>
[2020-10-05T17:12:54,866][DEBUG][logstash.runner          ] monitoring.elasticsearch.username: "logstash_system"
[2020-10-05T17:12:54,870][DEBUG][logstash.runner          ] monitoring.elasticsearch.ssl.verification_mode: "certificate"
[2020-10-05T17:12:54,874][DEBUG][logstash.runner          ] monitoring.elasticsearch.sniffing: false
[2020-10-05T17:12:54,878][DEBUG][logstash.runner          ] monitoring.collection.pipeline.details.enabled: true
[2020-10-05T17:12:54,891][DEBUG][logstash.runner          ] monitoring.collection.config.enabled: true
[2020-10-05T17:12:54,894][DEBUG][logstash.runner          ] node.uuid: ""
[2020-10-05T17:12:54,897][DEBUG][logstash.runner          ] --------------- Logstash Settings -------------------
[2020-10-05T17:12:55,134][WARN ][logstash.config.source.multilocal] Ignoring the 'pipelines.yml' file because modules or command line options are specified
[2020-10-05T17:12:55,311][DEBUG][logstash.agent           ] Setting up metric collection
[2020-10-05T17:12:55,435][DEBUG][logstash.instrument.periodicpoller.os] Starting {:polling_interval=>5, :polling_timeout=>120}
[2020-10-05T17:12:55,457][DEBUG][logstash.instrument.periodicpoller.cgroup] One or more required cgroup files or directories not found: /proc/self/cgroup, /sys/fs/cgroup/cpuacct, /sys/fs/cgroup/cpu
[2020-10-05T17:12:55,732][DEBUG][logstash.instrument.periodicpoller.jvm] Starting {:polling_interval=>5, :polling_timeout=>120}
[2020-10-05T17:12:56,046][DEBUG][logstash.instrument.periodicpoller.jvm] collector name {:name=>"ParNew"}
[2020-10-05T17:12:56,114][DEBUG][logstash.instrument.periodicpoller.jvm] collector name {:name=>"ConcurrentMarkSweep"}
[2020-10-05T17:12:56,175][DEBUG][logstash.instrument.periodicpoller.persistentqueue] Starting {:polling_interval=>5, :polling_timeout=>120}
[2020-10-05T17:12:56,246][DEBUG][logstash.instrument.periodicpoller.deadletterqueue] Starting {:polling_interval=>5, :polling_timeout=>120}
[2020-10-05T17:12:56,455][DEBUG][logstash.agent           ] Starting agent
[2020-10-05T17:12:56,798][DEBUG][logstash.config.source.local.configpathloader] Skipping the following files while reading config since they don't match the specified glob pattern {:files=>["/Users/Javier/ELK/Data/cars.csv"]}
[2020-10-05T17:12:56,807][DEBUG][logstash.config.source.local.configpathloader] Reading config file {:config_file=>"/Users/Javier/ELK/Data/logstash-cars.conf"}
[2020-10-05T17:12:56,973][DEBUG][logstash.agent           ] Converging pipelines state {:actions_count=>1}
[2020-10-05T17:12:57,002][DEBUG][logstash.agent           ] Executing action {:action=>LogStash::PipelineAction::Create/pipeline_id:main}
[2020-10-05T17:12:59,768][DEBUG][org.logstash.secret.store.SecretStoreFactory] Attempting to exists or secret store with implementation: org.logstash.secret.store.backend.JavaKeyStore
[2020-10-05T17:13:00,779][DEBUG][logstash.instrument.periodicpoller.cgroup] One or more required cgroup files or directories not found: /proc/self/cgroup, /sys/fs/cgroup/cpuacct, /sys/fs/cgroup/cpu
[2020-10-05T17:13:00,914][DEBUG][org.reflections.Reflections] going to scan these urls:
jar:file:/Users/Javier/ELK/logstash-7.9.2/logstash-core/lib/jars/logstash-core.jar!/
[2020-10-05T17:13:01,165][INFO ][org.reflections.Reflections] Reflections took 235 ms to scan 1 urls, producing 22 keys and 45 values 
[2020-10-05T17:13:01,228][DEBUG][org.reflections.Reflections] expanded subtype co.elastic.logstash.api.Plugin -> co.elastic.logstash.api.Input
[2020-10-05T17:13:01,232][DEBUG][org.reflections.Reflections] expanded subtype co.elastic.logstash.api.Plugin -> co.elastic.logstash.api.Codec
[2020-10-05T17:13:01,238][DEBUG][logstash.instrument.periodicpoller.jvm] collector name {:name=>"ParNew"}
[2020-10-05T17:13:01,238][DEBUG][org.reflections.Reflections] expanded subtype org.jruby.RubyBasicObject -> org.jruby.RubyObject
[2020-10-05T17:13:01,240][DEBUG][org.reflections.Reflections] expanded subtype java.lang.Cloneable -> org.jruby.RubyBasicObject
[2020-10-05T17:13:01,244][DEBUG][logstash.instrument.periodicpoller.jvm] collector name {:name=>"ConcurrentMarkSweep"}
[2020-10-05T17:13:01,245][DEBUG][org.reflections.Reflections] expanded subtype org.jruby.runtime.builtin.IRubyObject -> org.jruby.RubyBasicObject
[2020-10-05T17:13:01,247][DEBUG][org.reflections.Reflections] expanded subtype java.io.Serializable -> org.jruby.RubyBasicObject
[2020-10-05T17:13:01,255][DEBUG][org.reflections.Reflections] expanded subtype java.lang.Comparable -> org.jruby.RubyBasicObject
[2020-10-05T17:13:01,292][DEBUG][org.reflections.Reflections] expanded subtype org.jruby.runtime.marshal.CoreObjectType -> org.jruby.RubyBasicObject
[2020-10-05T17:13:01,317][DEBUG][org.reflections.Reflections] expanded subtype org.jruby.runtime.builtin.InstanceVariables -> org.jruby.RubyBasicObject
[2020-10-05T17:13:01,323][DEBUG][org.reflections.Reflections] expanded subtype org.jruby.runtime.builtin.InternalVariables -> org.jruby.RubyBasicObject
[2020-10-05T17:13:01,326][DEBUG][org.reflections.Reflections] expanded subtype co.elastic.logstash.api.Plugin -> co.elastic.logstash.api.Output
[2020-10-05T17:13:01,329][DEBUG][org.reflections.Reflections] expanded subtype co.elastic.logstash.api.Metric -> co.elastic.logstash.api.NamespacedMetric
[2020-10-05T17:13:01,346][DEBUG][org.reflections.Reflections] expanded subtype java.security.SecureClassLoader -> java.net.URLClassLoader
[2020-10-05T17:13:01,348][DEBUG][org.reflections.Reflections] expanded subtype java.lang.ClassLoader -> java.security.SecureClassLoader
[2020-10-05T17:13:01,351][DEBUG][org.reflections.Reflections] expanded subtype java.io.Closeable -> java.net.URLClassLoader
[2020-10-05T17:13:01,352][DEBUG][org.reflections.Reflections] expanded subtype java.lang.AutoCloseable -> java.io.Closeable
[2020-10-05T17:13:01,355][DEBUG][org.reflections.Reflections] expanded subtype java.lang.Comparable -> java.lang.Enum
[2020-10-05T17:13:01,357][DEBUG][org.reflections.Reflections] expanded subtype java.io.Serializable -> java.lang.Enum
[2020-10-05T17:13:01,361][DEBUG][org.reflections.Reflections] expanded subtype co.elastic.logstash.api.Plugin -> co.elastic.logstash.api.Filter
[2020-10-05T17:13:01,893][DEBUG][logstash.plugins.registry] On demand adding plugin to the registry {:name=>"file", :type=>"input", :class=>LogStash::Inputs::File}
[2020-10-05T17:13:02,340][DEBUG][logstash.plugins.registry] On demand adding plugin to the registry {:name=>"plain", :type=>"codec", :class=>LogStash::Codecs::Plain}
[2020-10-05T17:13:02,422][DEBUG][logstash.codecs.plain    ] config LogStash::Codecs::Plain/@id = "plain_d136da91-8285-4c22-866e-620ede516687"
[2020-10-05T17:13:02,425][DEBUG][logstash.codecs.plain    ] config LogStash::Codecs::Plain/@enable_metric = true
[2020-10-05T17:13:02,427][DEBUG][logstash.codecs.plain    ] config LogStash::Codecs::Plain/@charset = "UTF-8"
[2020-10-05T17:13:02,525][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@start_position = "beginning"
[2020-10-05T17:13:02,531][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@path = ["cars.csv"]
[2020-10-05T17:13:02,538][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@id = "c48d56b7777f48599cb1995bad9618663c5c59ef3808f382e16c406fd5b744fc"
[2020-10-05T17:13:02,549][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@sincedb_path = "/dev/null"
[2020-10-05T17:13:02,552][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@enable_metric = true
[2020-10-05T17:13:02,577][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@codec = <LogStash::Codecs::Plain id=>"plain_d136da91-8285-4c22-866e-620ede516687", enable_metric=>true, charset=>"UTF-8">
[2020-10-05T17:13:02,582][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@add_field = {}
[2020-10-05T17:13:02,599][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@stat_interval = 1.0
[2020-10-05T17:13:02,612][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@discover_interval = 15
[2020-10-05T17:13:02,627][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@sincedb_write_interval = 15.0
[2020-10-05T17:13:02,629][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@delimiter = "\n"
[2020-10-05T17:13:02,634][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@close_older = 3600.0
[2020-10-05T17:13:02,637][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@mode = "tail"
[2020-10-05T17:13:02,640][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@file_completed_action = "delete"
[2020-10-05T17:13:02,642][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@sincedb_clean_after = 1209600.0
[2020-10-05T17:13:02,644][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@file_chunk_size = 32768
[2020-10-05T17:13:02,646][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@file_chunk_count = 140737488355327
[2020-10-05T17:13:02,648][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@file_sort_by = "last_modified"
[2020-10-05T17:13:02,650][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@file_sort_direction = "asc"
[2020-10-05T17:13:02,652][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@exit_after_read = false
[2020-10-05T17:13:02,659][DEBUG][logstash.inputs.file     ] config LogStash::Inputs::File/@check_archive_validity = false
[2020-10-05T17:13:03,165][DEBUG][logstash.plugins.registry] On demand adding plugin to the registry {:name=>"csv", :type=>"filter", :class=>LogStash::Filters::CSV}
[2020-10-05T17:13:03,320][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@separator = ","
[2020-10-05T17:13:03,370][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@columns = ["maker", "model", "mileage", "manufacture_year", "engine_displacement", "engine_power", "body_type", "color_slug", "stk_year", "transmission", "door_count", "seat_count", "fuel_type", "date_created", "date_last_seen", "price_eur"]
[2020-10-05T17:13:03,375][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@id = "cdd42d9d750c98f6676c9039a2f93e1bded9a7b82d46e3e5b84b3b699a4692b9"
[2020-10-05T17:13:03,384][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@enable_metric = true
[2020-10-05T17:13:03,387][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@add_tag = []
[2020-10-05T17:13:03,400][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@remove_tag = []
[2020-10-05T17:13:03,402][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@add_field = {}
[2020-10-05T17:13:03,406][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@remove_field = []
[2020-10-05T17:13:03,408][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@periodic_flush = false
[2020-10-05T17:13:03,434][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@source = "message"
[2020-10-05T17:13:03,436][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@quote_char = "\""
[2020-10-05T17:13:03,438][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@autogenerate_column_names = true
[2020-10-05T17:13:03,440][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@skip_header = false
[2020-10-05T17:13:03,442][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@skip_empty_columns = false
[2020-10-05T17:13:03,450][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@skip_empty_rows = false
[2020-10-05T17:13:03,452][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@convert = {}
[2020-10-05T17:13:03,454][DEBUG][logstash.filters.csv     ] config LogStash::Filters::CSV/@autodetect_column_names = false
[2020-10-05T17:13:03,508][DEBUG][logstash.plugins.registry] On demand adding plugin to the registry {:name=>"mutate", :type=>"filter", :class=>LogStash::Filters::Mutate}
[2020-10-05T17:13:03,557][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@convert = {"mileage"=>"integer"}
[2020-10-05T17:13:03,561][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@id = "ce4f8d6c5110aea5c69ba45397145eb31da4a08de00434b4b87b0978e9d08b41"
[2020-10-05T17:13:03,563][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@enable_metric = true
[2020-10-05T17:13:03,566][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_tag = []
[2020-10-05T17:13:03,568][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_tag = []
[2020-10-05T17:13:03,570][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_field = {}
[2020-10-05T17:13:03,572][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_field = []
[2020-10-05T17:13:03,574][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@periodic_flush = false
[2020-10-05T17:13:03,626][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@tag_on_failure = "_mutate_error"
[2020-10-05T17:13:03,654][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@convert = {"price_eur"=>"integer"}
[2020-10-05T17:13:03,659][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@id = "48b28af846dc9cbf1d930f6876da8d16968bdbd36caa7a8c260f7a7eb1084abc"
[2020-10-05T17:13:03,670][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@enable_metric = true
[2020-10-05T17:13:03,675][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_tag = []
[2020-10-05T17:13:03,677][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_tag = []
[2020-10-05T17:13:03,679][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_field = {}
[2020-10-05T17:13:03,681][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_field = []
[2020-10-05T17:13:03,684][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@periodic_flush = false
[2020-10-05T17:13:03,686][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@tag_on_failure = "_mutate_error"
[2020-10-05T17:13:03,705][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@convert = {"engine_power"=>"integer"}
[2020-10-05T17:13:03,709][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@id = "e7fb45c405d8a1ae2aabfb3930ab0eca045ed1c9dea0bfcb038bddf14d0bbea3"
[2020-10-05T17:13:03,711][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@enable_metric = true
[2020-10-05T17:13:03,721][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_tag = []
[2020-10-05T17:13:03,739][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_tag = []
[2020-10-05T17:13:03,746][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_field = {}
[2020-10-05T17:13:03,750][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_field = []
[2020-10-05T17:13:03,756][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@periodic_flush = false
[2020-10-05T17:13:03,763][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@tag_on_failure = "_mutate_error"
[2020-10-05T17:13:03,782][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@convert = {"door_count"=>"integer"}
[2020-10-05T17:13:03,786][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@id = "df7d9200b926679e8415a22005d098822dd7d2c08dd5b1834ef10c241eaf893e"
[2020-10-05T17:13:03,789][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@enable_metric = true
[2020-10-05T17:13:03,794][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_tag = []
[2020-10-05T17:13:03,796][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_tag = []
[2020-10-05T17:13:03,797][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_field = {}
[2020-10-05T17:13:03,799][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_field = []
[2020-10-05T17:13:03,820][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@periodic_flush = false
[2020-10-05T17:13:03,826][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@tag_on_failure = "_mutate_error"
[2020-10-05T17:13:03,853][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@convert = {"seat_count"=>"integer"}
[2020-10-05T17:13:03,858][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@id = "869be2429d0be2e6e08bbb9ed93eafea57ce2857307bd8407e4254e11d4a7d0b"
[2020-10-05T17:13:03,860][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@enable_metric = true
[2020-10-05T17:13:03,861][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_tag = []
[2020-10-05T17:13:03,864][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_tag = []
[2020-10-05T17:13:03,866][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@add_field = {}
[2020-10-05T17:13:03,869][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@remove_field = []
[2020-10-05T17:13:03,870][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@periodic_flush = false
[2020-10-05T17:13:03,872][DEBUG][logstash.filters.mutate  ] config LogStash::Filters::Mutate/@tag_on_failure = "_mutate_error"
[2020-10-05T17:13:03,879][DEBUG][logstash.plugins.registry] On demand adding plugin to the registry {:name=>"elasticsearch", :type=>"output", :class=>LogStash::Outputs::ElasticSearch}
[2020-10-05T17:13:04,045][DEBUG][logstash.codecs.plain    ] config LogStash::Codecs::Plain/@id = "plain_7fcfc333-5e0c-4b83-9d25-ee875a77eb2a"
[2020-10-05T17:13:04,047][DEBUG][logstash.codecs.plain    ] config LogStash::Codecs::Plain/@enable_metric = true
[2020-10-05T17:13:04,050][DEBUG][logstash.codecs.plain    ] config LogStash::Codecs::Plain/@charset = "UTF-8"
[2020-10-05T17:13:04,149][WARN ][logstash.outputs.elasticsearch] You are using a deprecated config setting "document_type" set in elasticsearch. Deprecated settings will continue to work, but are scheduled for removal from logstash in the future. Document types are being deprecated in Elasticsearch 6.0, and removed entirely in 7.0. You should avoid this feature If you have any questions about this, please visit the #logstash channel on freenode irc. {:name=>"document_type", :plugin=><LogStash::Outputs::ElasticSearch index=>"cars", id=>"1ccb6d17d167a3bcebcd66ed1f1d93befe7adc586fc150e4e6534f4e71e996cb", hosts=>[http://localhost:9200], document_type=>"sold_cars", enable_metric=>true, codec=><LogStash::Codecs::Plain id=>"plain_7fcfc333-5e0c-4b83-9d25-ee875a77eb2a", enable_metric=>true, charset=>"UTF-8">, workers=>1, manage_template=>true, template_overwrite=>false, doc_as_upsert=>false, script_type=>"inline", script_lang=>"painless", script_var_name=>"event", scripted_upsert=>false, retry_initial_interval=>2, retry_max_interval=>64, retry_on_conflict=>1, ilm_enabled=>"auto", ilm_pattern=>"{now/d}-000001", ilm_policy=>"logstash-policy", ecs_compatibility=>:disabled, action=>"index", ssl_certificate_verification=>true, sniffing=>false, sniffing_delay=>5, timeout=>60, pool_max=>1000, pool_max_per_route=>100, resurrect_delay=>5, validate_after_inactivity=>10000, http_compression=>false>}
[2020-10-05T17:13:04,211][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@index = "cars"
[2020-10-05T17:13:04,213][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@id = "1ccb6d17d167a3bcebcd66ed1f1d93befe7adc586fc150e4e6534f4e71e996cb"
[2020-10-05T17:13:04,215][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@hosts = [http://localhost:9200]
[2020-10-05T17:13:04,229][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@document_type = "sold_cars"
[2020-10-05T17:13:04,231][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@enable_metric = true
[2020-10-05T17:13:04,233][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@codec = <LogStash::Codecs::Plain id=>"plain_7fcfc333-5e0c-4b83-9d25-ee875a77eb2a", enable_metric=>true, charset=>"UTF-8">
[2020-10-05T17:13:04,235][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@workers = 1
[2020-10-05T17:13:04,237][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@manage_template = true
[2020-10-05T17:13:04,260][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@template_overwrite = false
[2020-10-05T17:13:04,263][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@parent = nil
[2020-10-05T17:13:04,265][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@join_field = nil
[2020-10-05T17:13:04,267][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@upsert = ""
[2020-10-05T17:13:04,268][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@doc_as_upsert = false
[2020-10-05T17:13:04,273][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@script = ""
[2020-10-05T17:13:04,275][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@script_type = "inline"
[2020-10-05T17:13:04,279][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@script_lang = "painless"
[2020-10-05T17:13:04,281][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@script_var_name = "event"
[2020-10-05T17:13:04,283][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@scripted_upsert = false
[2020-10-05T17:13:04,285][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@retry_initial_interval = 2
[2020-10-05T17:13:04,287][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@retry_max_interval = 64
[2020-10-05T17:13:04,314][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@retry_on_conflict = 1
[2020-10-05T17:13:04,317][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@pipeline = nil
[2020-10-05T17:13:04,330][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@ilm_enabled = "auto"
[2020-10-05T17:13:04,333][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@ilm_pattern = "{now/d}-000001"
[2020-10-05T17:13:04,335][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@ilm_policy = "logstash-policy"
[2020-10-05T17:13:04,338][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@ecs_compatibility = :disabled
[2020-10-05T17:13:04,363][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@action = "index"
[2020-10-05T17:13:04,366][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@ssl_certificate_verification = true
[2020-10-05T17:13:04,373][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@sniffing = false
[2020-10-05T17:13:04,378][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@sniffing_delay = 5
[2020-10-05T17:13:04,384][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@timeout = 60
[2020-10-05T17:13:04,389][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@failure_type_logging_whitelist = []
[2020-10-05T17:13:04,391][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@pool_max = 1000
[2020-10-05T17:13:04,394][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@pool_max_per_route = 100
[2020-10-05T17:13:04,397][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@resurrect_delay = 5
[2020-10-05T17:13:04,399][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@validate_after_inactivity = 10000
[2020-10-05T17:13:04,403][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@http_compression = false
[2020-10-05T17:13:04,406][DEBUG][logstash.outputs.elasticsearch] config LogStash::Outputs::ElasticSearch/@custom_headers = {}
[2020-10-05T17:13:04,524][DEBUG][logstash.plugins.registry] On demand adding plugin to the registry {:name=>"stdout", :type=>"output", :class=>LogStash::Outputs::Stdout}
[2020-10-05T17:13:04,568][DEBUG][logstash.plugins.registry] On demand adding plugin to the registry {:name=>"rubydebug", :type=>"codec", :class=>LogStash::Codecs::RubyDebug}
[2020-10-05T17:13:04,646][DEBUG][logstash.codecs.rubydebug] config LogStash::Codecs::RubyDebug/@id = "rubydebug_44a81e64-03f0-4b08-aee9-5f9e0246b069"
[2020-10-05T17:13:04,649][DEBUG][logstash.codecs.rubydebug] config LogStash::Codecs::RubyDebug/@enable_metric = true
[2020-10-05T17:13:04,651][DEBUG][logstash.codecs.rubydebug] config LogStash::Codecs::RubyDebug/@metadata = false
[2020-10-05T17:13:06,453][DEBUG][logstash.instrument.periodicpoller.cgroup] One or more required cgroup files or directories not found: /proc/self/cgroup, /sys/fs/cgroup/cpuacct, /sys/fs/cgroup/cpu
[2020-10-05T17:13:06,486][DEBUG][logstash.instrument.periodicpoller.jvm] collector name {:name=>"ParNew"}
[2020-10-05T17:13:06,505][DEBUG][logstash.instrument.periodicpoller.jvm] collector name {:name=>"ConcurrentMarkSweep"}
[2020-10-05T17:13:07,316][DEBUG][logstash.outputs.stdout  ] config LogStash::Outputs::Stdout/@id = "666ae06c71a53b7e3ec8c5a021c20a62c5ca48a6ce47a684fb229ec0b49d175f"
[2020-10-05T17:13:07,321][DEBUG][logstash.outputs.stdout  ] config LogStash::Outputs::Stdout/@enable_metric = true
[2020-10-05T17:13:07,324][DEBUG][logstash.outputs.stdout  ] config LogStash::Outputs::Stdout/@codec = <LogStash::Codecs::RubyDebug id=>"rubydebug_44a81e64-03f0-4b08-aee9-5f9e0246b069", enable_metric=>true, metadata=>false>
[2020-10-05T17:13:07,326][DEBUG][logstash.outputs.stdout  ] config LogStash::Outputs::Stdout/@workers = 1
[2020-10-05T17:13:07,420][DEBUG][logstash.javapipeline    ] Starting pipeline {:pipeline_id=>"main"}
[2020-10-05T17:13:07,521][DEBUG][logstash.outputs.elasticsearch][main] Normalizing http path {:path=>nil, :normalized=>nil}
[2020-10-05T17:13:08,525][INFO ][logstash.outputs.elasticsearch][main] Elasticsearch pool URLs updated {:changes=>{:removed=>[], :added=>[http://localhost:9200/]}}
[2020-10-05T17:13:08,539][DEBUG][logstash.outputs.elasticsearch][main] Running health check to see if an Elasticsearch connection is working {:healthcheck_url=>http://localhost:9200/, :path=>"/"}
[2020-10-05T17:13:09,185][WARN ][logstash.outputs.elasticsearch][main] Restored connection to ES instance {:url=>"http://localhost:9200/"}
[2020-10-05T17:13:09,366][INFO ][logstash.outputs.elasticsearch][main] ES Output version determined {:es_version=>7}
[2020-10-05T17:13:09,382][WARN ][logstash.outputs.elasticsearch][main] Detected a 6.x and above cluster: the `type` event field won't be used to determine the document _type {:es_version=>7}
[2020-10-05T17:13:09,579][INFO ][logstash.outputs.elasticsearch][main] New Elasticsearch output {:class=>"LogStash::Outputs::ElasticSearch", :hosts=>["http://localhost:9200"]}
[2020-10-05T17:13:09,615][DEBUG][logstash.filters.csv     ][main] CSV parsing options {:col_sep=>",", :quote_char=>"\""}
[2020-10-05T17:13:09,703][INFO ][logstash.outputs.elasticsearch][main] Using a default mapping template {:es_version=>7, :ecs_compatibility=>:disabled}
[2020-10-05T17:13:09,859][INFO ][logstash.outputs.elasticsearch][main] Attempting to install template {:manage_template=>{"index_patterns"=>"logstash-*", "version"=>60001, "settings"=>{"index.refresh_interval"=>"5s", "number_of_shards"=>1}, "mappings"=>{"dynamic_templates"=>[{"message_field"=>{"path_match"=>"message", "match_mapping_type"=>"string", "mapping"=>{"type"=>"text", "norms"=>false}}}, {"string_fields"=>{"match"=>"*", "match_mapping_type"=>"string", "mapping"=>{"type"=>"text", "norms"=>false, "fields"=>{"keyword"=>{"type"=>"keyword", "ignore_above"=>256}}}}}], "properties"=>{"@timestamp"=>{"type"=>"date"}, "@version"=>{"type"=>"keyword"}, "geoip"=>{"dynamic"=>true, "properties"=>{"ip"=>{"type"=>"ip"}, "location"=>{"type"=>"geo_point"}, "latitude"=>{"type"=>"half_float"}, "longitude"=>{"type"=>"half_float"}}}}}}}
[2020-10-05T17:13:09,907][DEBUG][logstash.outputs.elasticsearch][main] Found existing Elasticsearch template. Skipping template management {:name=>"logstash"}
[2020-10-05T17:13:09,950][INFO ][logstash.javapipeline    ][main] Starting pipeline {:pipeline_id=>"main", "pipeline.workers"=>4, "pipeline.batch.size"=>125, "pipeline.batch.delay"=>50, "pipeline.max_inflight"=>500, "pipeline.sources"=>["/Users/Javier/ELK/Data/logstash-cars.conf"], :thread=>"#<Thread:0x7d9ee1da run>"}
[2020-10-05T17:13:11,485][DEBUG][logstash.instrument.periodicpoller.cgroup] One or more required cgroup files or directories not found: /proc/self/cgroup, /sys/fs/cgroup/cpuacct, /sys/fs/cgroup/cpu
[2020-10-05T17:13:11,606][DEBUG][logstash.instrument.periodicpoller.jvm] collector name {:name=>"ParNew"}
[2020-10-05T17:13:11,609][DEBUG][logstash.instrument.periodicpoller.jvm] collector name {:name=>"ConcurrentMarkSweep"}
[2020-10-05T17:13:12,228][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-csv{"separator"=>",", "columns"=>["maker", "model", "mileage", "manufacture_year", "engine_displacement", "engine_power", "body_type", "color_slug", "stk_year", "transmission", "door_count", "seat_count", "fuel_type", "date_created", "date_last_seen", "price_eur"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:14:1:```
csv {
separator => ","

columns => ['maker', 'model', 'mileage', 'manufacture_year', 'engine_displacement', 'engine_power', 'body_type', 'color_slug', 'stk_year', 'transmission', 'door_count', 'seat_count', 'fuel_type', 'date_created', 'date_last_seen', 'price_eur']

}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@53e5cb12
[2020-10-05T17:13:12,228][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-csv{"separator"=>",", "columns"=>["maker", "model", "mileage", "manufacture_year", "engine_displacement", "engine_power", "body_type", "color_slug", "stk_year", "transmission", "door_count", "seat_count", "fuel_type", "date_created", "date_last_seen", "price_eur"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:14:1:```
csv {
separator => ","

columns => ['maker', 'model', 'mileage', 'manufacture_year', 'engine_displacement', 'engine_power', 'body_type', 'color_slug', 'stk_year', 'transmission', 'door_count', 'seat_count', 'fuel_type', 'date_created', 'date_last_seen', 'price_eur']

}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@53e5cb12
[2020-10-05T17:13:12,228][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-csv{"separator"=>",", "columns"=>["maker", "model", "mileage", "manufacture_year", "engine_displacement", "engine_power", "body_type", "color_slug", "stk_year", "transmission", "door_count", "seat_count", "fuel_type", "date_created", "date_last_seen", "price_eur"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:14:1:```
csv {
separator => ","

columns => ['maker', 'model', 'mileage', 'manufacture_year', 'engine_displacement', 'engine_power', 'body_type', 'color_slug', 'stk_year', 'transmission', 'door_count', 'seat_count', 'fuel_type', 'date_created', 'date_last_seen', 'price_eur']

}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@53e5cb12
[2020-10-05T17:13:12,228][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-csv{"separator"=>",", "columns"=>["maker", "model", "mileage", "manufacture_year", "engine_displacement", "engine_power", "body_type", "color_slug", "stk_year", "transmission", "door_count", "seat_count", "fuel_type", "date_created", "date_last_seen", "price_eur"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:14:1:```
csv {
separator => ","

columns => ['maker', 'model', 'mileage', 'manufacture_year', 'engine_displacement', 'engine_power', 'body_type', 'color_slug', 'stk_year', 'transmission', 'door_count', 'seat_count', 'fuel_type', 'date_created', 'date_last_seen', 'price_eur']

}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@53e5cb12
[2020-10-05T17:13:12,855][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["mileage", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:21:1:```
mutate {convert => ["mileage", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,854][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["mileage", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:21:1:```
mutate {convert => ["mileage", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,854][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["mileage", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:21:1:```
mutate {convert => ["mileage", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,912][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["price_eur", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:22:1:```
mutate {convert => ["price_eur", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,915][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["mileage", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:21:1:```
mutate {convert => ["mileage", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,914][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["price_eur", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:22:1:```
mutate {convert => ["price_eur", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,954][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["price_eur", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:22:1:```
mutate {convert => ["price_eur", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,954][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["engine_power", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:23:1:```
mutate {convert => ["engine_power", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,961][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["engine_power", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:23:1:```
mutate {convert => ["engine_power", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,974][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["price_eur", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:22:1:```
mutate {convert => ["price_eur", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,987][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["engine_power", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:23:1:```
mutate {convert => ["engine_power", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:12,992][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["door_count", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:24:1:```
mutate {convert => ["door_count", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:13,004][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["door_count", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:24:1:```
mutate {convert => ["door_count", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:13,005][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["engine_power", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:23:1:```
mutate {convert => ["engine_power", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:13,023][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["door_count", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:24:1:```
mutate {convert => ["door_count", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:13,031][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["seat_count", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:25:1:```
mutate {convert => ["seat_count", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:13,037][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["seat_count", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:25:1:```
mutate {convert => ["seat_count", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:13,038][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["door_count", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:24:1:```
mutate {convert => ["door_count", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:13,058][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled output
 P[output-elasticsearch{"hosts"=>["http://localhost:9200"], "index"=>"cars", "document_type"=>"sold_cars"}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:29:2:```
elasticsearch {
		hosts => ["http://localhost:9200"]
		index => "cars"
		document_type => "sold_cars"
	}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@3fdc2b9c
[2020-10-05T17:13:13,063][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled output
 P[output-elasticsearch{"hosts"=>["http://localhost:9200"], "index"=>"cars", "document_type"=>"sold_cars"}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:29:2:```
elasticsearch {
		hosts => ["http://localhost:9200"]
		index => "cars"
		document_type => "sold_cars"
	}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@3fdc2b9c
[2020-10-05T17:13:13,068][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["seat_count", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:25:1:```
mutate {convert => ["seat_count", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:13,089][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled output
 P[output-elasticsearch{"hosts"=>["http://localhost:9200"], "index"=>"cars", "document_type"=>"sold_cars"}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:29:2:```
elasticsearch {
		hosts => ["http://localhost:9200"]
		index => "cars"
		document_type => "sold_cars"
	}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@3fdc2b9c
[2020-10-05T17:13:13,092][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled output
 P[output-stdout{}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:34:2:```
stdout {}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@3fdc2b9c
[2020-10-05T17:13:13,102][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled filter
 P[filter-mutate{"convert"=>["seat_count", "integer"]}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:25:1:```
mutate {convert => ["seat_count", "integer"]}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@8d7da797
[2020-10-05T17:13:13,107][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled output
 P[output-stdout{}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:34:2:```
stdout {}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@3fdc2b9c
[2020-10-05T17:13:13,115][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled output
 P[output-elasticsearch{"hosts"=>["http://localhost:9200"], "index"=>"cars", "document_type"=>"sold_cars"}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:29:2:```
elasticsearch {
		hosts => ["http://localhost:9200"]
		index => "cars"
		document_type => "sold_cars"
	}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@3fdc2b9c
[2020-10-05T17:13:13,116][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled output
 P[output-stdout{}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:34:2:```
stdout {}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@3fdc2b9c
[2020-10-05T17:13:13,140][DEBUG][org.logstash.config.ir.CompiledPipeline][main] Compiled output
 P[output-stdout{}|[file]/Users/Javier/ELK/Data/logstash-cars.conf:34:2:```
stdout {}
```] 
 into 
 org.logstash.config.ir.compiler.ComputeStepSyntaxElement@3fdc2b9c
[2020-10-05T17:13:13,158][INFO ][logstash.javapipeline    ][main] Pipeline Java execution initialization time {"seconds"=>3.2}
[2020-10-05T17:13:13,793][DEBUG][logstash.javapipeline    ][main] Shutdown waiting for worker thread {:pipeline_id=>"main", :thread=>"#<Thread:0x30357a33 run>"}
[2020-10-05T17:13:13,895][DEBUG][logstash.javapipeline    ][main] Shutdown waiting for worker thread {:pipeline_id=>"main", :thread=>"#<Thread:0x70383475 dead>"}
[2020-10-05T17:13:13,897][DEBUG][logstash.javapipeline    ][main] Shutdown waiting for worker thread {:pipeline_id=>"main", :thread=>"#<Thread:0x71b90583 dead>"}
[2020-10-05T17:13:13,898][DEBUG][logstash.javapipeline    ][main] Shutdown waiting for worker thread {:pipeline_id=>"main", :thread=>"#<Thread:0x7068a19e dead>"}
[2020-10-05T17:13:13,904][DEBUG][logstash.filters.csv     ][main] Closing {:plugin=>"LogStash::Filters::CSV"}
[2020-10-05T17:13:13,912][DEBUG][logstash.pluginmetadata  ][main] Removing metadata for plugin cdd42d9d750c98f6676c9039a2f93e1bded9a7b82d46e3e5b84b3b699a4692b9
[2020-10-05T17:13:13,916][DEBUG][logstash.filters.mutate  ][main] Closing {:plugin=>"LogStash::Filters::Mutate"}
[2020-10-05T17:13:13,919][DEBUG][logstash.pluginmetadata  ][main] Removing metadata for plugin ce4f8d6c5110aea5c69ba45397145eb31da4a08de00434b4b87b0978e9d08b41
[2020-10-05T17:13:13,920][DEBUG][logstash.filters.mutate  ][main] Closing {:plugin=>"LogStash::Filters::Mutate"}
[2020-10-05T17:13:13,922][DEBUG][logstash.pluginmetadata  ][main] Removing metadata for plugin e7fb45c405d8a1ae2aabfb3930ab0eca045ed1c9dea0bfcb038bddf14d0bbea3
[2020-10-05T17:13:13,923][DEBUG][logstash.filters.mutate  ][main] Closing {:plugin=>"LogStash::Filters::Mutate"}
[2020-10-05T17:13:13,925][DEBUG][logstash.pluginmetadata  ][main] Removing metadata for plugin 48b28af846dc9cbf1d930f6876da8d16968bdbd36caa7a8c260f7a7eb1084abc
[2020-10-05T17:13:13,927][DEBUG][logstash.filters.mutate  ][main] Closing {:plugin=>"LogStash::Filters::Mutate"}
[2020-10-05T17:13:13,929][DEBUG][logstash.pluginmetadata  ][main] Removing metadata for plugin 869be2429d0be2e6e08bbb9ed93eafea57ce2857307bd8407e4254e11d4a7d0b
[2020-10-05T17:13:13,932][DEBUG][logstash.filters.mutate  ][main] Closing {:plugin=>"LogStash::Filters::Mutate"}
[2020-10-05T17:13:13,934][DEBUG][logstash.pluginmetadata  ][main] Removing metadata for plugin df7d9200b926679e8415a22005d098822dd7d2c08dd5b1834ef10c241eaf893e
[2020-10-05T17:13:13,939][DEBUG][logstash.outputs.elasticsearch][main] Closing {:plugin=>"LogStash::Outputs::ElasticSearch"}
[2020-10-05T17:13:13,957][DEBUG][logstash.outputs.elasticsearch][main] Stopping sniffer
[2020-10-05T17:13:13,960][DEBUG][logstash.outputs.elasticsearch][main] Stopping resurrectionist
[2020-10-05T17:13:14,506][DEBUG][logstash.outputs.elasticsearch][main] Waiting for in use manticore connections
[2020-10-05T17:13:14,529][DEBUG][logstash.outputs.elasticsearch][main] Closing adapter #<LogStash::Outputs::ElasticSearch::HttpClient::ManticoreAdapter:0x3566dd2e>
[2020-10-05T17:13:14,550][DEBUG][logstash.pluginmetadata  ][main] Removing metadata for plugin 1ccb6d17d167a3bcebcd66ed1f1d93befe7adc586fc150e4e6534f4e71e996cb
[2020-10-05T17:13:14,562][DEBUG][logstash.outputs.stdout  ][main] Closing {:plugin=>"LogStash::Outputs::Stdout"}
[2020-10-05T17:13:14,569][DEBUG][logstash.pluginmetadata  ][main] Removing metadata for plugin 666ae06c71a53b7e3ec8c5a021c20a62c5ca48a6ce47a684fb229ec0b49d175f
[2020-10-05T17:13:14,582][DEBUG][logstash.javapipeline    ][main] Pipeline terminated by worker error {:pipeline_id=>"main", :exception=>#<ArgumentError: File paths must be absolute, relative path specified: cars.csv>, :backtrace=>["/Users/Javier/ELK/logstash-7.9.2/vendor/bundle/jruby/2.5.0/gems/logstash-input-file-4.2.1/lib/logstash/inputs/file.rb:283:in `block in register'", "org/jruby/RubyArray.java:1809:in `each'", "/Users/Javier/ELK/logstash-7.9.2/vendor/bundle/jruby/2.5.0/gems/logstash-input-file-4.2.1/lib/logstash/inputs/file.rb:281:in `register'", "/Users/Javier/ELK/logstash-7.9.2/logstash-core/lib/logstash/java_pipeline.rb:226:in `block in register_plugins'", "org/jruby/RubyArray.java:1809:in `each'", "/Users/Javier/ELK/logstash-7.9.2/logstash-core/lib/logstash/java_pipeline.rb:225:in `register_plugins'", "/Users/Javier/ELK/logstash-7.9.2/logstash-core/lib/logstash/java_pipeline.rb:359:in `start_inputs'", "/Users/Javier/ELK/logstash-7.9.2/logstash-core/lib/logstash/java_pipeline.rb:309:in `start_workers'", "/Users/Javier/ELK/logstash-7.9.2/logstash-core/lib/logstash/java_pipeline.rb:183:in `run'", "/Users/Javier/ELK/logstash-7.9.2/logstash-core/lib/logstash/java_pipeline.rb:134:in `block in start'"], "pipeline.sources"=>["/Users/Javier/ELK/Data/logstash-cars.conf"], :thread=>"#<Thread:0x7d9ee1da run>"}
[2020-10-05T17:13:14,643][ERROR][logstash.agent           ] Failed to execute action {:id=>:main, :action_type=>LogStash::ConvergeResult::FailedAction, :message=>"Could not execute action: PipelineAction::Create<main>, action_result: false", :backtrace=>nil}
[2020-10-05T17:13:14,722][DEBUG][logstash.agent           ] Starting puma
[2020-10-05T17:13:14,762][DEBUG][logstash.agent           ] Trying to start WebServer {:port=>9600}
[2020-10-05T17:13:14,785][DEBUG][logstash.instrument.periodicpoller.os] Stopping
[2020-10-05T17:13:14,809][DEBUG][logstash.instrument.periodicpoller.jvm] Stopping
[2020-10-05T17:13:14,816][DEBUG][logstash.instrument.periodicpoller.persistentqueue] Stopping
[2020-10-05T17:13:14,823][DEBUG][logstash.instrument.periodicpoller.deadletterqueue] Stopping
[2020-10-05T17:13:14,844][DEBUG][logstash.agent           ] Shutting down all pipelines {:pipelines_count=>0}
[2020-10-05T17:13:14,852][DEBUG][logstash.agent           ] Converging pipelines state {:actions_count=>0}
[2020-10-05T17:13:14,896][DEBUG][logstash.api.service     ] [api-service] start
[2020-10-05T17:13:15,413][INFO ][logstash.agent           ] Successfully started Logstash API endpoint {:port=>9600}
[2020-10-05T17:13:20,045][INFO ][logstash.runner          ] Logstash shut down.
[2020-10-05T17:13:20,076][ERROR][org.logstash.Logstash    ] java.lang.IllegalStateException: Logstash stopped processing because of an error: (SystemExit) exit
