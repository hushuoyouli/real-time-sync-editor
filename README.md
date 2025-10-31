# real-time-sync-editor
导入 Behavior Designer.package后
1.将ExportBehaviorTreeUtil.cs与ExportBehaviorTreeUtilForServer.cs 放到目录Assets\Behavior Designer\Runtime下
2.将BehaviorTreeUtil.cs 放到目录Assets\Behavior Designer\Editor下

采用unity store里面的Behavior Designer的编辑器生成树的文件，再利用ExportBehaviorTreeUtil.cs 里面的函数进行导出
1.不要使用里面的共享变量（多余）
2.不要使用里面的打断块（多余）
