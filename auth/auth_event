import 'package:equatable/equatable.dart';
import 'package:meta/meta.dart';

abstract class AuthenticationEvent extends Equatable{
  const AuthenticationEvent();
  @override
  List<Object> get props=>[];
}

class AppStarted extends AuthenticationEvent{
}

class LoggedIn extends AuthenticationEvent {
  final String token;
  final String name;
  final String password;

  const LoggedIn({required this.token,required this.name,required this.password});

  @override
  String toString() => 'LoggedIn { name: $name token: $token }';
}

class SignedUp extends AuthenticationEvent {
  final String token;
  final String name;
  final String password;

  const SignedUp({required this.token,required this.name,required this.password});

  @override
  String toString() => 'LoggedIn { token: $name token: $token }';
}

class LoggedOut extends AuthenticationEvent{}
