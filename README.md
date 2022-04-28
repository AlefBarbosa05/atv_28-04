# atv_28-04
import 'package:flutter/material.dart';

const Color darkBlue = Color.fromARGB(255, 18, 32, 47);

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      theme: ThemeData.dark().copyWith(
        scaffoldBackgroundColor: darkBlue,
      ),
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        body: Center(
          child: MyWidget(),
        ),
      ),
    );
  }
}

class MyWidget extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container(
        decoration: BoxDecoration(
          borderRadius: BorderRadius.circular(40.0),
        color: Colors.white,),
        height: 600,
        width: 600,
        child: Column(
            mainAxisAlignment: MainAxisAlignment.spaceBetween,
            children: [
              Container(
                decoration: const BoxDecoration(
                    color: Colors.blue,
                    borderRadius: BorderRadius.all(
                      Radius.circular(10.0),
                    )),
                height: 70,
                width: 300,
              ),
              Row(
                  
                  mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                  children: [
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.blue,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 70,
                      width: 70,
                    ),
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.blue,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 70,
                      width: 70,
                    ),
                  ]),
              Container(
                decoration: const BoxDecoration(
                    color: Colors.blue,
                    borderRadius: BorderRadius.all(
                      Radius.circular(10.0),
                    )),
                height: 70,
                width: 300,
              ),
              Row(
                  crossAxisAlignment: CrossAxisAlignment.center,
                  mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                  children: [
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.blue,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 70,
                      width: 70,
                    ),
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.blue,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 70,
                      width: 70,
                    ),
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.blue,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 70,
                      width: 70,
                    ),
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.blue,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 70,
                      width: 70,
                    ),
                  ]),
              Container(
                  width: 300,
                  decoration: const BoxDecoration(
                      color: Colors.blue,
                      borderRadius: BorderRadius.all(
                        Radius.circular(10.0),
                      )),
                  child: Column(children: [
                        const SizedBox(
                      height: 25,
                    ),
                    Row(
                        crossAxisAlignment: CrossAxisAlignment.center,
                        mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                        children: [
                          Container(
                            decoration: const BoxDecoration(
                                color: Colors.yellow,
                                borderRadius: BorderRadius.all(
                                  Radius.circular(10.0),
                                )),
                            height: 75,
                            width: 75,
                          ),
                          Container(
                            decoration: const BoxDecoration(
                                color: Colors.black,
                                borderRadius: BorderRadius.all(
                                  Radius.circular(10.0),
                                )),
                            height: 75,
                            width: 75,
                          ),
                        ]),
                    const SizedBox(
                      height: 30,
                    ),
                    Row(
                        crossAxisAlignment: CrossAxisAlignment.center,
                        mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                        children: [
                          Container(
                            decoration: const BoxDecoration(
                                color: Colors.white,
                                borderRadius: BorderRadius.all(
                                  Radius.circular(10.0),
                                )),
                            height: 75,
                            width: 75,
                          ),
                          Container(
                            decoration: const BoxDecoration(
                                color: Colors.pink,
                                borderRadius: BorderRadius.all(
                                  Radius.circular(10.0),
                                )),
                            height: 75,
                            width: 75,
                          ),
                      
                        ]),
                        const SizedBox(
                      height: 20,
                    ),
                  ]))
            ]));
  }
}
