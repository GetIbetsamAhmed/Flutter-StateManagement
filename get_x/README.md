# What is GETx ? 

GetX is not only a state management library, but instead, it is a microframework combined with route management and dependency injection. It aims to deliver top-of-the-line development experience in an extra lightweight but powerful solution for Flutter

## The three pillars of GetX

1) State management: GetX has two state managers. One is a simple state manager used with the GetBuilder function, and the other is a reactive state manager used with Getx or Obx. We will be talking about it in detail below.

2) Route management: whether navigating between screens, showing SnackBars, popping dialog boxes, or adding bottom sheets without the use of context, GetX has you covered. I will not write details on route management because it is beyond the scope of this article, but indeed a few examples to get an idea of how GetX syntax simplicity works

3) Dependency management: GetX has a simple yet powerful solution for dependency management using controllers. With just a single line of code, it can be accessed from the view without using an inherited widget or context. Typically, you would instantiate a class within a class, but with GetX, you are instantiating with the Get instance, which will be available throughout your application

## Value-added features of GetX

1) Internationalization: translations with key-value maps, various language support, using translations with singulars, plurals, and parameters. Changing the application’s locale using only the Get word throughout the app

2) Validation: email and password validations are also covered by GetX. Now you do not need to install a separate validation package

3) Storage: GetX also provides fast and extra light synchronous key-value memory backup of data entirely written in Dart that easily integrates with the GetX core package

4) Themes: switching between light and dark themes is made simple with GetX

5) Responsive view: if you are building an application for different screen sizes, you just need to extend with GetView, and you can quickly develop your UI, which will be responsive for desktop, tablet, phone, and watch
