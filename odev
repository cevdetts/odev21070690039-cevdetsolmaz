import 'package:flutter/material.dart';
import 'package:splashscreen/splashscreen.dart';

void main()
{
    runApp(new Uygulamam(
      home: new Uygulamam(),
  
    ));
}

class Uygulamam extends StatefulWidget
{
    @override
  _UygulamamState createState() => new _UygulamamState();
}

class _UygulamamState extends State<Uygulamam> {
    @override
  Widget build(BuildContext context) {
        return new SplashScreen(
            seconds: 5,
            navigateAfterSeconds: new AfterSplash(),
            title: new Text(
              'Açılış Ekranına Hoşgeldiniz!',
              style: new TextStyle(fontWeight: FontWeight.bold, fontSize: 20.0),
    
            ),
            image: new Image.network(
                'https://onursahin.net/wp-content/uploads/2021/01/c6dae25c982ce81623b3f363bd4a7291.png'),
            backgroundColor: Colors.white,
            styleTextUnderTheLoader: new TextStyle(),
            photoSize: 200.0,
            loaderColor: Colors.black);
    }
}

class AfterSplash extends StatelessWidget
{
    @override
  Widget build(BuildContext context) {
        return new Scaffold(
          appBar: new AppBar(
              title: new Text("Anasayfa"), automaticallyImplyLeading: false),
          body: new Center(
            child: new Text(
              "Ana Sayfa",
              style: new TextStyle(fontWeight: FontWeight.bold, fontSize: 30.0),
    
            ),
    
          ),
    
        );
    }
}
