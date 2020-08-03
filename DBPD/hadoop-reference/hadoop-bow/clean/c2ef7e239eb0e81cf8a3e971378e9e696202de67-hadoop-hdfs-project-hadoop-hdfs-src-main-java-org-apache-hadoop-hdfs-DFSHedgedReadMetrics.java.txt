HDFS-6124. Add final modifier to class members. (Contributed by Suresh Srinivas)

git-svn-id: https://svn.apache.org/repos/asf/hadoop/common/trunk@1581124 13f79535-47bb-0310-9956-ffa450edef68

-  public AtomicLong hedgedReadOps = new AtomicLong();
-  public AtomicLong hedgedReadOpsWin = new AtomicLong();
-  public AtomicLong hedgedReadOpsInCurThread = new AtomicLong();
+  public final AtomicLong hedgedReadOps = new AtomicLong();
+  public final AtomicLong hedgedReadOpsWin = new AtomicLong();
+  public final AtomicLong hedgedReadOpsInCurThread = new AtomicLong();
