# MinEBay
 MinEBay is a Java application for managing classified ads, featuring user accounts, ad listings, and categorized ad management. Users can post, acquire, and track ads in different states, while navigating through ads by category and date.

The core structure of this project revolves around three main classes:

-User: Represents each user on the MinEBay platform. A user manages three types of ads: ads they authored that are still open for buyers (state OPEN), ads they authored that have found buyers (state CLOSED), and ads published by others that they have acquired (state PURCHASE).
-ClassifiedAd: Represents a single classified ad posted on MinEBay.
-CategorizedAdList: Represents a list of ads grouped by category, allowing users to navigate through ads in chronological order (from the most recent to the oldest). It also supports filtering by specific categories, making it easier for users to find what they are looking for. This class is utilized within the User class to manage the different types of ads.
Additionally, the project includes two pre-defined enums: Category and AdState, which are used to manage ad categories and their respective states.
