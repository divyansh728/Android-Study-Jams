# Android-Study-Jams

## I Used: Room DataBase, Work Manager,Navigation Component, SharedPreferences, Dynamic Permission, Camera image capture feature, Lottie Animation, Kotlin, ViewPager, 3rd party library etc.

It is a Notes making App, in our day-to-day life each of us faces some incidents or gain some important informations 
that we want to note somewhere so that if We forgot it, we can check it in those notes, This app is very helpful in that
you can make notes list in this of any type even it is suitable to note your personal expenses, shoppings etc.
Students can also make notes related to their study in this application, it is simple to operate for users.

## Room DataBase:- 
RoomDatabase provides direct access to the underlying database implementation but you should prefer using Dao classes.

Nested classes
class	RoomDatabase.Builder<T extends RoomDatabase>
Builder for RoomDatabase. 
class	RoomDatabase.Callback
Callback for RoomDatabase. 
enum	RoomDatabase.JournalMode
Journal modes for SQLite database. 
class	RoomDatabase.MigrationContainer
A container to hold migrations. 

## Navigation Component:-  
Navigation graph: An XML resource that contains all navigation-related information in one centralized location.
This includes all of the individual content areas within your app, called destinations, as well as the possible paths that a usercan take through your app.
NavHost: An empty container that displays destinations from your navigation graph. The Navigation component contains a 
default NavHost implementation, NavHostFragment, that displays fragment destinations.
NavController: An object that manages app navigation within a NavHost. The NavController orchestrates the swapping of 
destination content in the NavHost as users move throughout your app.

## Lottie Animation:-
Lottie is an open source animation file format that’s tiny, high quality, interactive, and can be manipulated at runtime.
The top 500 apps on the App store now use Lottie to engage users and enhance conversions.

## Work Manager:-
To create some work for WorkManager to run, extend the Worker class and override the doWork() method. For example, 
to create a Worker that uploads images, you can do the following:

 class UploadWorker(appContext: Context, workerParams: WorkerParameters):
       Worker(appContext, workerParams) {
   override fun doWork(): Result {

       // Do the work here--in this case, upload the images.
       uploadImages()

       // Indicate whether the work finished successfully with the Result
       return Result.success()
   }
}

## Shared Preferences:-
One of the most Interesting Data Storage options Android provides its users is Shared Preferences. Shared Preferences is the way
in which one can store and retrieve small amounts of primitive data as key/value pairs to a file on the device storage such as
String, int, float, Boolean that make up your preferences in an XML file inside the app on the device storage. 
Shared Preferences can be thought of as a dictionary or a key/value pair. For example, you might have a key being 
“username” and for the value, you might store the user’s username. And then you could retrieve that by its key (here username).
