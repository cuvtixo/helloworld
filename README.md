# helloworld
hello world
+-------------
+    Small package manager which download, compile -if needed- and install packages from sources.
+
+    This tool has several goals in mind:
+        1. It does not depend on repository.
+        2. Be always up to date, since packages builds from the very last PKGBUILD in master Arch branch.
+        3. Download from tool source.
+        4. Compile the package.
+
+Usage: hello-world
+---------------
+
+OPTIONS:
+
+    PACKAGES:
+    -s <pkg>: search package
+    -i <pkg>: download and compile package
+    -g <group>: install all packages inside a arch group
+    -a: install all packages from all groups
+
+    REPOSITORY:
+    -l: list arch groups
+    -p <group>: list packages from group
+    -u: update arch repository
+
+    SORT TOOLS:
+    -h: sort tools into main directory [~/hello default]
+    -D <dir>: change default main directory
+
+    FLAGS:
+    -f: force# hello-world
