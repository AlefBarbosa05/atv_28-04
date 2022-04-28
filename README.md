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
        color: Colors.white,
        child: Column(
            mainAxisAlignment: MainAxisAlignment.spaceBetween,
            children: [
              Container(
                decoration: const BoxDecoration(
                    color: Colors.green,
                    borderRadius: BorderRadius.all(
                      Radius.circular(10.0),
                    )),
                height: 50,
                width: 150,
              ),
              Row(
                  //   crossAxisAlignment: CrossAxisAlignment.center,
                  mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                  children: [
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.green,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 50,
                      width: 50,
                    ),
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.green,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 50,
                      width: 50,
                    ),
                  ]),
              Container(
                decoration: const BoxDecoration(
                    color: Colors.green,
                    borderRadius: BorderRadius.all(
                      Radius.circular(10.0),
                    )),
                height: 50,
                width: 150,
              ),
              Row(
                  crossAxisAlignment: CrossAxisAlignment.center,
                  mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                  children: [
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.green,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 50,
                      width: 50,
                    ),
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.green,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 50,
                      width: 50,
                    ),
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.green,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 50,
                      width: 50,
                    ),
                    Container(
                      decoration: const BoxDecoration(
                          color: Colors.green,
                          borderRadius: BorderRadius.all(
                            Radius.circular(10.0),
                          )),
                      height: 50,
                      width: 50,
                    ),
                  ]),
              Container(
                  width: 200,
                  decoration: const BoxDecoration(
                      color: Colors.green,
                      borderRadius: BorderRadius.all(
                        Radius.circular(10.0),
                      )),
                  child: Column(children: [
                        const SizedBox(
                      height: 20,
                    ),
                    Row(
                        crossAxisAlignment: CrossAxisAlignment.center,
                        mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                        children: [
                          Container(
                            decoration: const BoxDecoration(
                                color: Colors.purple,
                                borderRadius: BorderRadius.all(
                                  Radius.circular(10.0),
                                )),
                            height: 50,
                            width: 50,
                          ),
                          Container(
                            decoration: const BoxDecoration(
                                color: Colors.pink,
                                borderRadius: BorderRadius.all(
                                  Radius.circular(10.0),
                                )),
                            height: 50,
                            width: 50,
                          ),
                        ]),
                    const SizedBox(
                      height: 20,
                    ),
                    Row(
                        crossAxisAlignment: CrossAxisAlignment.center,
                        mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                        children: [
                          Container(
                            decoration: const BoxDecoration(
                                color: Colors.red,
                                borderRadius: BorderRadius.all(
                                  Radius.circular(10.0),
                                )),
                            height: 50,
                            width: 50,
                          ),
                          Container(
                            decoration: const BoxDecoration(
                                color: Colors.blue,
                                borderRadius: BorderRadius.all(
                                  Radius.circular(10.0),
                                )),
                            height: 50,
                            width: 50,
                          ),
                      
                        ]),
                        const SizedBox(
                      height: 20,
                    ),
                  ]))
            ]));
  }
}
