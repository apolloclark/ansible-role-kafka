# Ansible Role: heartbeat

Ansible Role to install and configure Apache Kafka for Ubuntu.


## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `vars/main-2.0.0.yml`).
You can overload the variables by creating a dictionary called "kafka", ex:

    kafka:
      version: 2.0.0

## Dependencies

Apache Zookeeper

## Example Playbook

    - hosts: all
      roles:
        - apolloclark.zookeeper
        - apolloclark.kafka

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Apollo Clark](https://www.apolloclark.com/)
