### `DomainExceptionCode` Convention
La convenzione  è:
```
<Aggregate/Entity>_<Scenario/Opertation/Field (opzionale)>_<Condition>_Error
```

Esempi coerenti:
```
BookingItem_Cancellation_TooLateForNoShow_Error (aggregate_operation_condition_error)
SalesOrder_SalesOrderGuid_CannotBeEmpty_Error (aggregate_field_condition_error)
SalesOrder_CannotBeFound_Error (aggregate_condition_error)
SalesOrderItem_SalesOrderItemID_NeedAtLeastOne_Error (entity_field_condition_error)
```

Sono però presenti alcune varianti:

### `ValidationErrorCode`
La convenzione  è:
```
<Aggregate/Entity>_<Field (opzionale)>_<ValidationRule>
```

Esempi coerenti:
```
Timetable_DateValidityFrom_Invalid (aggregate_field_validationRule)
TimetableItem_DateValidityFrom_BeforeTimetableStart (entity_field_validationRule)
SalesOrderItem_IsProcessed_CannotBeTrue (entity_field_validationRule)
SalesOrderItem_ShouldExist (entity_validationRule)
```