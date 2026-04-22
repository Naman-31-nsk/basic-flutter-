
import 'package:flutter/material.dart';
import '../../../core/theme/app_text_styles.dart';
import '../../../shared/widgets/custom_button.dart';
import '../../../shared/widgets/custom_textfield.dart';

class LoginScreen extends StatelessWidget {
  const LoginScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Padding(
        padding: const EdgeInsets.all(20),

        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [

            const Text(
              "Welcome Back",
              style: AppTextStyles.heading,
            ),

            const SizedBox(height: 30),

            const CustomTextField(
              hintText: "Enter Email",
            ),

            const SizedBox(height: 15),

            const CustomTextField(
              hintText: "Enter Password",
              obscureText: true,
            ),

            const SizedBox(height: 25),

            CustomButton(
              text: "Login",
              onPressed: () {},
            ),
          ],
        ),
      ),
    );
  }
}
