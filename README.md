# referendums contract
This contract holds ...

## Actions
### create
#### Description:
Creates a new referendum system where users can vote.

#### Required permission: `referendums1@active`
#### Inline actions: 
N / A

#### Parameters: 
| Type | Name | Description |
| -- | -- | -- |
| uint64_t | referendum_id | Referendum id |
| name | creator | Creator's name |
| time_point | start_date | Referendum's start day |
| time:point | end_date | Referendum's end date |
| day_percentage | quorum_config | Configuring Quorum Requirements |
| day_percentage | majority_config | Configuration of the requirements for the majority |

Note: See special data types section for more information
-- 

# Special data types
## day_percentage

| Type | Name |
| -- | -- |
| vector<common::types::day_percentage> | day_percentage |

### day_percentage composition
| Type | name |
| -- | -- |
| uint16_t | start day |
| uint16_t | percentage |

--

## 

