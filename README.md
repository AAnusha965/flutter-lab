import 'package:flutter/material.dart';
void main(){
  runApp(MyApp());
}
class MyApp extends StatelessWidget{
  @override
  Widget build(BuildContext context){
    return MaterialApp(
      home:Scaffold(
        appBar: AppBar(
          title: Text('Flutter Row Example'),
        ),
        body: Center(
          child:Row( 
            mainAxisAlignment:MainAxisAlignment.spaceAround,
            crossAxisAlignment: 
            CrossAxisAlignment.center,
            children: [
              Icon(
                Icons.home,
                color: const Color.fromARGB(255, 231, 19, 19),
                size: 40,
              ),
              Text(
               'Namastee!',
               style:
               TextStyle(fontSize:20,
               fontWeight: FontWeight.bold),
                 ),
                 ElevatedButton(
                  onPressed:(){
                  },
                  child: Text("click here!!")
                  ),
              
            ],
            ),
        ),
      ),
    );
  }}
