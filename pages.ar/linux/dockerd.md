# dockerd

> هي عملية مستمرة تعمل في الخلفية تبدأها لتتحكم في حاويات الدوكر.
> لمزيد من التفاصيل: <https://docs.docker.com/engine/reference/commandline/dockerd/>.

- قم بتشغيل دوكر في الخلفية:

`dockerd`

- قم بتشغيل دوكر في الخلفية واجعله يستمع علي منفذ معين (يونكس وبروتوكول ضبط الإرسال):

`dockerd --host unix://{{path/to/tmp.sock}} --host tcp://{{ip}}`

- قم بتشغيل دوكر في الخلفية برقم عملية معين:

`dockerd --pidfile {{path/to/pid_file}}`

- قم بتشغيل دوكر في وضع التصحيح واكتشاف الأخطاء:

`dockerd --debug`

- قم بتشغيل دوكر وحدد له مستوي سجل معين:

`dockerd --log-level {{debug|info|warn|error|fatal}}`
