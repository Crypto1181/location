# location
flutterflow location Ip tracker 
@override
Widget build(BuildContext context) {
  return Scaffold(
    appBar: AppBar(
      title: Text("SlidingUpPanelExample"),
    ),
    body: SlidingUpPanel(
      panel: Center(
        child: Text("This is the sliding Widget"),
      ),
      body: Center(
        child: Text("This is the Widget behind the sliding panel"),
      ),
    ),
  );
}
