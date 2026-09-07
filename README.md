import 'package:flutter/material.dart';

void main() {
  runApp(const ChatApp());
}

class ChatApp extends StatelessWidget {
  const ChatApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'ChatConnect',
      home: Scaffold(
        appBar: AppBar(
          title: const Text('ChatConnect'),
        ),
        body: const Center(
          child: Text('Welcome to ChatConnect!'),
        ),
      ),
    );
  }
}
