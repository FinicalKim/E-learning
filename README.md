# E-learning


@startuml
package "E-Learning App" {
    [Frontend Application] -down-> [User Management Service]
    [Frontend Application] -down-> [Question Bank Service]
    [Frontend Application] -down-> [Progress Tracking Service]
    [Frontend Application] -down-> [Notification Service]
    
    [User Management Service] --> [User Database]
    [Question Bank Service] --> [Question Database]
    [Progress Tracking Service] --> [Progress Database]
    [Notification Service] --> [Notification Database]
}
@enduml